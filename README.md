# 🖼️🔐 LSB Image Steganography in Python (Google Colab Ready)

A Python project that demonstrates **Least Significant Bit (LSB) Steganography** for securely hiding text messages inside images without visible distortion. Built for **cybersecurity education**, real-world **steganographic applications**, and **digital watermarking**.


---

## 📚 Table of Contents

- [📌 Overview](#-overview)
- [🔍 How It Works](#-how-it-works)
- [✨ Features](#-features)
- [⚙️ Installation](#️-installation)
- [📄 License](#-license)

---

## 📌 Overview

This project allows you to:

- Encode a secret message inside an image using LSB steganography
- Decode and extract that message from the image
- Visualize differences between the original and encoded images
- Integrate with **Google Drive** in **Google Colab** for seamless storage

> 🔐 Steganography hides *the existence* of a message — unlike encryption which just scrambles the content.

---

## 🔍 How It Works

### 🔧 Encoding Steps:
1. Convert the input message into binary
2. Modify the **least significant bits** of each pixel’s RGB values
3. Embed message bits sequentially and terminate with a delimiter (`=====`)

### 🧠 Decoding Steps:
1. Read LSBs from the image pixels
2. Reconstruct binary data
3. Stop at the delimiter and convert to readable text

---

## ✨ Features

- ✅ RGB-channel LSB embedding
- ✅ Delimiter-based message extraction
- ✅ Visual diff viewer (with Matplotlib)
- ✅ File verification & error handling
- ✅ Google Colab & Drive integration

---

## ⚙️ Installation

### 🔁 Clone the Repository

```bash
git clone [https://github.com/sanjaychaurasia04/lsb-image-steganography-Project](https://github.com/Sanjaychaurasia04/LSB-Steganography-Projec).git
cd lsb-image-steganography
```
# 🧩 Install Dependencies
```bash
pip install opencv-python numpy matplotlib
```
# 📁 Google Colab Users
Use drive.mount('/content/drive', force_remount=True) to access Google Drive from Colab.

# 📄 License
This project is licensed under the MIT License.
See the LICENSE file for more details.


