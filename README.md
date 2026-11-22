🔥 BaziGarr QR Generator

<p align="center">
  <b>A Stylish Gradient QR Code Generator for Python</b>
</p><p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Platform-Android%20%7C%20Linux-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Interface-Terminal-black?style=for-the-badge">
  <img src="https://img.shields.io/badge/Output-PNG-orange?style=for-the-badge">
</p>🚀 About

BaziGarr QR Generator is a Python-based QR code generation tool designed for Android, Termux, and Linux environments.

It generates beautiful QR codes with a modern Green → Cyan → Blue gradient design and displays them directly in the terminal.

You can also save your generated QR codes as PNG images with a perfectly centered gradient filename.

Simple, stylish, and easy to use!

✨ Features

- 🎨 Beautiful Green-Cyan-Blue gradient QR design.
- 📱 QR code preview directly in the terminal.
- 🌈 Gradient-colored filename in terminal and saved images.
- 🎯 Centered filename below the QR code.
- 🖼️ High-resolution PNG image generation.
- 💾 Optional image saving with a Y/N confirmation.
- 🔗 Automatic HTTPS prefix for URLs without a protocol.
- 🔄 Generate multiple QR codes without restarting.
- 📂 Automatic output directory creation.
- 🛡️ High QR error correction (Level H).
- ⚡ Simple interactive terminal interface.
- 🏷️ Custom filename support.

📸 Preview

<p align="center">
  <i>Terminal preview and generated QR image screenshots can be added here.</i>
</p>📋 Requirements

- Python 3.x
- qrcode
- Pillow
- FIGlet 

📦 Installation

1. Clone the repository

git clone https://github.com/hckrr-bazigarr/BaziGarr-QR-Generator.git

2. Enter the project directory

cd BaziGarr-QR-Generator

3. Install Python dependencies

pip install qrcode[pil] Pillow

4. Install FIGlet

Termux:

pkg update
pkg install figlet

Kali Linux / Debian:

sudo apt update
sudo apt install figlet

▶️ Usage

Run the script:

python3 BaziGarrQR.py

Enter your URL:

🔗 Enter Link/URL: https://example.com

Enter your preferred QR image filename:

📝 Enter Name of the QR-Image: MyWebsite

The QR code will be generated and displayed in your terminal.

You will then see:

💾 SAVE THIS IMAGE? (y/n):

- Enter "y" to save the QR image.
- Enter "n" to skip saving.

After generation, choose:

1. Next Link 🔗
2. Exit ❌

📂 Output Location

Generated QR images are saved in:

/storage/emulated/0/Pictures/QR_CODE

Example:

Pictures/
└── QR_CODE/
    ├── MyWebsite.png
    ├── YouTube.png
    └── GitHub.png

⚙️ Customization

You can customize the QR design by modifying these values in the Python script:

GREEN = (0, 200, 115)
CYAN = (0, 185, 180)
BLUE = (0, 155, 225)

MODULE_SIZE = 12
BORDER = 4

🛠️ Built With

- Python – Core programming language.
- qrcode – QR code generation.
- Pillow (PIL) – Image creation and gradient rendering.
- FIGlet – ASCII terminal banner.

👨‍💻 Author

BaziGarr

Created with ❤️ and Python.

⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

Contributions, suggestions, and improvements are welcome.

---

<p align="center">
  <b>🔥 BAZIGARR QR GENERATOR 🔥</b>
  <br>
  <i>Generate. Customize. Scan.</i>
</p>
