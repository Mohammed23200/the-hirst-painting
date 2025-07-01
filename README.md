# 🖼️ Dot Painting with Turtle - Day 18 of #100DaysOfCode

<div align="center">

![Python Version](https://img.shields.io/badge/Python-3.13.1-blue.svg)
![GUI](https://img.shields.io/badge/GUI-Turtle%20Graphics-yellow)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Last Updated](https://img.shields.io/badge/Updated-June%202025-brightgreen)

My first experience with GUI in Python, creating colorful **dot paintings** using the turtle module and RGB color palettes extracted from real images 🎨

[Preview](#preview) • [Features](#features) • [How-it-works](#how-it-works) • [Run-it](#run-it) • [License](#license)

</div>

---

## 📸 Preview

![image](https://github.com/user-attachments/assets/825ac1d4-dfda-4806-a0a3-20fc74837a88)

<!-- Replace with actual screenshot of the output window -->

---

## ✨ Features

- 🟣 Draws a **10x10 grid** of colorful dots
- 🌈 Uses real RGB color values from image extraction
- 🐢 Created with Python's turtle GUI module
- ⚡ Fast drawing using `.speed(0)` for animation
- 🎯 Fully customizable color palette
- 🖱️ Click screen to exit program

---

## 📂 Project Structure

```bash
dot-painting/
├── dot_painting.py         # Main script
├── assets/
│   └── dot-painting-preview.png  # Screenshot (replace with yours)
├── README.md
└── LICENSE
```
🧠 How It Works
colormode(255) sets turtle to accept RGB colors

A predefined RGB palette is used (extracted via colorgram.py)

A turtle moves in grid pattern using loops

dot() draws each colorful circle

After each row, the turtle resets position and continues

💻 Run it Locally
bash
نسخ
تحرير
python dot_painting.py
✅ No external libraries needed
✅ Works on any Python 3.x version with turtle module (comes pre-installed)

🔧 Customize
Want bigger/smaller dots? → Change dot(15)

Change spacing? → Modify .forward(50)

Add your own color palette? → Paste RGB values in colors_rgb list

Want to extract from a custom image?

python
نسخ
تحرير
# Uncomment and use this (requires `colorgram.py`)
# import colorgram
# colors = colorgram.extract('your_image.jpg', 30)
📝 License
Licensed under MIT – feel free to use, modify, remix!

🙏 Acknowledgments
Inspired by Hirst-style dot paintings 🎨

Based on #100DaysOfCode by Dr. Angela Yu

Color palette extracted using colorgram.py

<div align="center"> Built with ❤️, `turtle`, and a lot of tiny dots </div> ```
