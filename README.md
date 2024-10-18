# 🔐 Secure Steganography and Cryptography System

This project implements a **secure steganography and cryptography system** that allows users to hide sensitive information within **image**, **audio**, and **video files**. The system employs advanced cryptographic algorithms to encrypt user data, which is then embedded within media files using steganographic techniques such as **LSB (Least Significant Bit)** and **RLSB (Randomized Least Significant Bit)**. This dual-layered approach ensures the confidentiality and security of sensitive data.

---

## 🛠️ Features

1. **Data Encryption**: Encrypt sensitive user data using a robust cryptographic algorithm.
2. **Steganographic Embedding**: Hide encrypted data within media files using LSB and RLSB techniques.
3. **New Algorithm Integration**: Combines cryptography and steganography to enhance security during the data hiding process.
4. **Media File Support**: Works with various file formats, including **images**, **audio**, and **video**.
5. **Steg Image Creation**: Generates a media file with embedded sensitive information.

---

## 🧠 Techniques Used

- **LSB (Least Significant Bit)**: A method of hiding data by modifying the least significant bit of the media file's pixel values.
- **RLSB (Randomized Least Significant Bit)**: An enhanced version of LSB that introduces randomness in data embedding to avoid detection.
- **Cryptography Algorithm**: Text is encrypted before being embedded using cryptographic algorithms, adding a layer of security.

---



## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/secure-steganography-cryptography-system.git
cd secure-steganography-cryptography-system
```

### 2. Install Dependencies

Install all required Python dependencies by running:


## 🛠️ Usage

### 1. Encrypt and Hide Data

Run the `main.py` file to encrypt the sensitive data and hide it within a media file:

```bash
python main.py
```

1. **Input the Text**: Enter the sensitive information you want to hide.
2. **Choose Media File**: Select the media file (image, audio, or video) where the data will be hidden.
3. **Steg Image Creation**: The system will encrypt the text, apply LSB and RLSB techniques, and create a new media file with the hidden data.

### 2. Extract and Decrypt Data

To extract the hidden data from a media file use the decoding button on same web page.

1. **Select Steganographic File**: Choose the media file that contains the hidden data.
2. **Decryption**: The system will extract the hidden data and decrypt it to reveal the original sensitive information.

---

## 🔑 Algorithm Workflow

1. **Text Encryption**: The user input is encrypted using a custom cryptographic algorithm.
2. **LSB and RLSB Techniques**: The encrypted text is embedded into the media file using LSB or RLSB techniques, depending on user preference.
3. **Steg Image Creation**: A steganographic image (or media file) is created with the embedded cipher text.

---
