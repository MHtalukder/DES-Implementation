# DES Encryption / Decryption Tool

## Author Information
**Name:** Md. Hannan Talukder  
**Course:** Cryptography & Network Security  
**University:** Daffodil International University  
**Roll:** 253-56-011  
**Date:** 30-11-2025  

---

## Description
This project is a Python implementation of the **DES (Data Encryption Standard)** algorithm.  
It allows users to **encrypt** and **decrypt** text using a **16-hexadecimal key**.  
The tool supports multiple blocks of plaintext by padding it to multiples of 8 bytes.

---

## Features
- DES key validation (16 hexadecimal characters)
- Encrypt plaintext to HEX ciphertext
- Decrypt HEX ciphertext to plaintext
- Padding for plaintext to ensure proper block size
- CBC-style processing for multiple 64-bit blocks
- Clear messages for invalid key or ciphertext

---

## Prerequisites
- Python 3.x installed on your system
- Basic understanding of running Python scripts

---

## How to Run

1. Clone or download this repository.
2. Open terminal or command prompt and navigate to the folder containing `des_implementation_253_56_011.py`.
3. Run the script:

```bash
python des_implementation_253_56_011.py
