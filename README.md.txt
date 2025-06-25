# 🔐 Image Encryption & Decryption using Java Swing

A simple Java Swing GUI application that encrypts and decrypts image files using XOR logic with a numeric key.

## 🚀 Features
- GUI interface built with Java Swing
- File selection using JFileChooser
- XOR-based reversible encryption
- Works on any image file
- Easy to use, clean layout

## 🧠 How It Works
1. You enter a number (like a secret key)
2. Click on “Open Image” and select an image file
3. The program reads the image file byte by byte
4. Each byte is XORed with the key
5. File is overwritten with encrypted data
6. Run again with same key to decrypt it back

## 💻 Requirements
- Java JDK 8 or higher
- Any OS with GUI (Windows/Linux/Mac)
- IDE like Eclipse/IntelliJ (optional)

## 📦 How to Run
```bash
javac ImageEncryption.java
java ImageEncryption
