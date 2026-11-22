🔥 BaziGarr QR Generator

<p align="center">
  <b>A Stylish Gradient QR Code Generator for Python</b>
</p><p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Platform-Termux%20%7C%20Android-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Interface-Terminal-black?style=for-the-badge">
  <img src="https://img.shields.io/badge/Output-PNG-orange?style=for-the-badge">
</p>---

🚀 About

BaziGarr QR Generator is a Python-based QR code generation tool designed for Android, Termux, and Linux environments.

Generate beautiful QR codes with a modern Green → Cyan → Blue gradient design, preview them directly in your terminal, and save them as PNG images with matching gradient-colored filenames.

Simple. Stylish. Powerful.

✨ Features

- 🎨 Beautiful Green-Cyan-Blue gradient QR design.
- 📱 QR code preview directly in the terminal.
- 🌈 Gradient-colored filename in terminal and saved images.
- 🎯 Centered filename below the QR code.
- 🖼️ PNG image generation.
- 💾 Optional image saving with Y/N confirmation.
- 🔗 Automatic HTTPS prefix for URLs without a protocol.
- 🔄 Generate multiple QR codes without restarting.
- 📂 Automatic output directory creation.
- 🛡️ High QR error correction (Level H).
- 🏷️ Custom QR image filenames.
- ⚡ Interactive terminal interface.
- 🎭 FIGlet ASCII terminal banner.

---

⚡ Installation Guide

Follow the steps below to install and run BaziGarr QR Generator.

📱 Installation on Termux

Step 1 — Install Git, Python and FIGlet

pkg update && pkg upgrade -y

pkg install git python figlet -y

Step 2 — Clone Repository

git clone https://github.com/csrb4zzigar-07/QR-CODE-GENERETOR.git

Step 3 — Open Project Directory

cd QR-CODE-GENERETOR

Step 4 — Install Python Dependencies

pip install -r requirements.txt

Step 5 — Run BaziGarr QR Generator

python3 "qr-code genretor"

---

🐉 Installation on Kali Linux

Step 1 — Update Packages

sudo apt update && sudo apt upgrade -y

Step 2 — Install Required Packages

sudo apt install git python3 python3-pip python3-venv figlet -y

Step 3 — Clone Repository

git clone https://github.com/csrb4zzigar-07/QR-CODE-GENERETOR.git

Step 4 — Open Project Directory

cd QR-CODE-GENERETOR

Step 5 — Create Virtual Environment

python3 -m venv .venv

Step 6 — Activate Virtual Environment

source .venv/bin/activate

Step 7 — Install Python Dependencies

pip install -r requirements.txt

Step 8 — Run BaziGarr QR Generator

python3 "qr-code genretor"

---

📸 Terminal Preview

<p align="center">
  <img src="terminal-preview.jpg" alt="BaziGarr QR Generator Terminal Preview" width="350">
</p><p align="center">
  <b>BAZIGARR QR GENERATOR</b>
  <br>
  <i>Beautiful gradient QR generation directly in the terminal.</i>
</p>---

🎯 How to Use

1. Enter a URL

🔗 Enter Link/URL: https://github.com

2. Enter QR Image Name

📝 Enter Name of the QR-Image: GitHub

3. Save Your QR Image

After generating the QR code, the program asks:

💾 SAVE THIS IMAGE? (y/n):

- Enter "y" to save the QR image.
- Enter "n" to skip saving.

4. Generate Another QR Code

1. Next Link 🔗
2. Exit ❌

Choose "1" to generate another QR code or "2" to exit.

---

📂 Output Location

Generated QR images are saved in:

/storage/emulated/0/Pictures/QR_CODE

Example directory structure:

Pictures/
└── QR_CODE/
    ├── GitHub.png
    ├── YouTube.png
    └── MyWebsite.png

Note: The default save location is configured for Android shared storage. On other Linux systems, change "SAVE_DIR" in the Python script to a suitable directory.

---

⚙️ Customization

Customize the QR gradient and appearance by modifying these settings:

GREEN = (0, 200, 115)
CYAN = (0, 185, 180)
BLUE = (0, 155, 225)

MODULE_SIZE = 12
BORDER = 4

---

📦 Dependencies

All required Python libraries are listed in "requirements.txt".

Install them using:

pip install -r requirements.txt

Built With

Technology| Purpose
Python| Core programming language
qrcode| QR code generation
Pillow| Image processing and gradient rendering
FIGlet| Terminal ASCII banner

---

📁 Project Structure

QR-CODE-GENERETOR/
│
├── README.md
├── requirements.txt
├── terminal-preview.jpg
└── qr-code genretor

---

👨‍💻 Author

BaziGarr

Created with ❤️ and Python.

⭐ Support the Project

If you like BaziGarr QR Generator:

- ⭐ Give this repository a Star.
- 🍴 Fork the repository.
- 💡 Share your suggestions.
- 🐛 Report bugs through GitHub Issues.
- 🤝 Contributions are welcome!

---

<p align="center">
  <b>🔥 BAZIGARR QR GENERATOR 🔥</b>
  <br>
  <i>Generate. Customize. Scan.</i>
  <br><br>
  Made with ❤️ by BaziGarr
</p>
