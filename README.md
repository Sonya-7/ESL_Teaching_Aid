# 🗺️ City Map Generator

![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Pillow](https://img.shields.io/badge/Powered%20by-Pillow-orange.svg)

Generate a **colorful city map** using Python and the [Pillow (PIL)](https://pillow.readthedocs.io/en/stable/) library.
The program draws a realistic grid of roads, sidewalks, and buildings, complete with street names and a legend.

Each run creates a structured, visually appealing city layout — great for **games, simulations, education,** or **procedural design**.

---

## 🚀 Features

* 🏙️ **Automatic Map Layout** – Generates a city grid with both horizontal and vertical roads.
* 🧱 **Buildings and Blocks** – Ten building types (e.g., *Hospital*, *Library*, *Cafe*) appear in distinct city blocks.
* 🛣️ **Detailed Roads** – Draws sidewalks, center lines, and consistent road spacing.
* 🪧 **Street Labels** – Adds readable names for all streets.
* 🎨 **Legend Section** – Displays building names and icons with matching colors.
* 💻 **Terminal Preview** – Optionally prints an ASCII preview in the terminal.

---

## 🧰 Technologies Used

* **Python 3.12+**
* **Random** – Layout variation
* **Pillow (PIL)** – Image generation and drawing
* **IPython.display** – Inline display in Jupyter notebooks

---

## 📦 Output

The script saves a generated map as:

```
map_with_buildings_and_legend.png
```

The image shows:

* A grid of named roads
* Color-coded buildings
* A right-hand legend explaining each building type

---

## 🧠 How It Works

1. **Setup and Configuration**
   Defines map size, colors, and layout grid.

2. **Road Drawing**
   Draws horizontal and vertical roads with sidewalks and dashed center lines.

3. **Building Placement**
   Calculates available blocks between roads and places one building per block, based on custom placement rules.

4. **Labels and Legend**
   Adds street names and a clean, alphabetized legend.

5. **Display and Save**
   Saves the map as a PNG file and shows a terminal preview.

---

## 🧩 Example Uses

* 🏗️ City planning or layout visualization
* 🕹️ Game or simulation map backgrounds
* 🧰 Procedural content generation experiments
* 🧮 Educational projects and classroom demonstrations
* 🎓 Teaching aid for introducing the concept of direction
* 💡 Python practice for learners exploring 2D drawing and spatial logic

---

## 🖼️ Example Output

<img width="25%" height="25%" alt="map_with_buildings_and_legend" src="https://github.com/user-attachments/assets/81e780b4-f252-48f4-8319-37c1a3cb7819" />


## ⚙️ How to Run

### 1️⃣ Install Dependencies

```bash
pip install pillow
```

### 2️⃣ Run the Script

```bash
python esl-teaching-aid-for-vocabulary-words.ipynb
```

### 3️⃣ View the Output

Check the generated file:

```
map_with_buildings_and_legend.png
```

Optional: Run in Jupyter or IPython to display the image inline.

---

## 🏗️ Project Goals

This project demonstrates how **Python can combine geometry, randomness, and design** to create a procedural city map.

It’s designed for learners who want to:

* Practice 2D layout logic
* Understand image generation with Pillow
* Explore procedural or randomized visual design

---

## 🪪 License

This project is licensed under the **MIT License**.
Feel free to use, modify, and share with attribution.

---
