# 🔐 Caesar Cipher Security Tool

A command-line Python application that demonstrates the fundamentals of classical cryptography using the **Caesar Cipher**. This project was developed as part of a cybersecurity internship to strengthen core programming and cryptography concepts.

## 🚀 Features

* Encrypt messages using a custom key
* Decrypt messages using the correct key
* Generate a random encryption key
* Brute-force attack simulation (tries all 25 possible keys)
* Save encryption/decryption history with timestamps
* View and clear history
* Message statistics (letters, words, digits, spaces, characters)
* Security analysis explaining the strengths and weaknesses of the Caesar Cipher
* Professional command-line interface with colored output and ASCII banner

## 🛠️ Technologies Used

* Python 3
* Colorama
* PyFiglet

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/caesar-cipher-security-tool.git
cd caesar-cipher-security-tool
```

Install the required libraries:

```bash
pip install colorama pyfiglet
```

Run the application:

```bash
python caesar_cipher_tool.py
```

## 📂 Project Structure

```
📦 Caesar-Cipher-Security-Tool
 ├── caesar_cipher_tool.py
 ├── history.txt
 ├── README.md
 └── requirements.txt
```

## 📖 How It Works

The Caesar Cipher encrypts text by shifting each letter of the alphabet by a specified number of positions.

Example:

```
Plaintext : HELLO
Key       : 3
Ciphertext: KHOOR
```

Decryption shifts the letters back by the same key to recover the original message.

## 🎯 Learning Objectives

This project demonstrates:

* Classical encryption techniques
* Cryptographic keys
* Encryption and decryption logic
* Brute-force attacks
* File handling in Python
* Modular programming
* Input validation
* Basic cybersecurity principles

## ⚠️ Disclaimer

The Caesar Cipher is a historical encryption algorithm and **is not secure for modern applications**. This project is intended solely for educational purposes and to demonstrate the fundamentals of cryptography.

## 👨‍💻 Author

Developed by **Haya Ajami** as part of a cybersecurity learning journey.

If you found this project interesting, feel free to ⭐ the repository.
