# 📱 QR Code Generator with Python

A simple and effective script to generate a **QR code** using Python. The QR code can be for a URL, text, contact info, or anything you want. The generated code is saved as an image file that you can use in print or digital media.

<img width="330" height="330" alt="image" src="https://github.com/user-attachments/assets/e66f2dd3-57b8-4cce-812c-d33b412ae923" />    

Advanced QR Code Generator using Python is a simple and enhanced Python program that generates a QR code for a URL with customized colors and error correction. It uses the qrcode library along with Pillow (PIL) for image processing. This version supports setting QR code version, error correction level, color customization, and saves the final image as a .png file.

 Advanced QR Code Generator ........................ <img width="410" height="410" alt="image" src="https://github.com/user-attachments/assets/0c4fb2be-a3f0-49e3-a808-9bf6c58b851f" />


---

## 📚 Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [Contact](#contact)

---

## ✅ Features

- 🔗 Convert any URL or text to a QR code
- 🖼️ Save the QR code as an image file
- ⚡ Simple and fast execution
- 💡 Beginner-friendly code using the `qrcode` library

---

## 🚀 Demo

```bash
Generates a QR code for: https://adityadhiman.in
Saves it as: mscube_youtube.png
```
**⚙️ Usage
Clone the repository or create a Python file:

bash

git clone https://github.com/aditibelwal007/qr-code-generator-python
cd qr-code-generator-python
Modify the URL or text inside qr_code.py if desired:

python

import qrcode as qr_code
img = qr_code.make("https://your-link.com")
img.save("your_qrcode_name.png")
Run the script:

bash

python qr_code.py
Your QR code image will be saved in the same directory.**

🧠 How It Works
Uses the qrcode library to create a QR code from a given string (usually a URL).

Generates an image object using qr_code.make(...).

Saves the image to a file using .save("filename.png").

🤝 Contributing
Contributions are welcome!

Fork the repo

Make your improvements

Submit a Pull Request

📬 Contact
For any queries or collaboration ideas:

🌐 Website: www.aditibelwal.dev

💼 GitHub: @aditibelwal007

🔗 LinkedIn: Aditi Belwal

<p align="center"> Made with ❤️ by <strong>Aditi Belwal</strong> </p> ```
