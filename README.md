# Chaotic-System
This project encrypts images using a chaotic system (Logistic Map). It converts an image into an unintelligible version visually. The image can be decrypted using the same key.
# Chaotic Image Encryption

This project implements **image encryption** using a chaotic system (Logistic Map). It encrypts an image into an unintelligible version, and it can be decrypted using the same key.

## Features
- Simple chaotic encryption using XOR with a Logistic Map.
- Works for color images (RGB).
- Easy to use and modify.

## Requirements
- Python 3.x
- Numpy
- Pillow (PIL)

Install required packages:
```bash
pip install numpy pillow
from chaotic_image_encryption import encrypt_image
encrypt_image('input.png', key=0.54321)
from chaotic_image_encryption import decrypt_image
decrypt_image('encrypted.png', key=0.54321)
