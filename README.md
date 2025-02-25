# imageSteganography
# 🖼️ Image Steganography  

## 🔍 Overview  
This project implements **Image Steganography**, allowing users to hide secret messages inside images using pixel manipulation techniques. It also supports decryption to extract hidden messages.  

## ✨ Features  
✅ Hide text inside an image  
✅ Extract hidden messages from an image  
✅ Password-protected encryption  
✅ Supports `.jpg` and `.png` image formats  
✅ Simple command-line interface (CLI)  

## 📌 How It Works  
The program modifies pixel values in an image to encode a message. The message is then retrieved using the **same password** for decryption.  

## 🚀 Installation  
Ensure you have **Python 3.x** installed. Then, install dependencies:  
```sh
pip install opencv-python
 Encoding (Hiding a Message)
python stego.py --encode -i input.jpg -m "Your secret message" -o encrypted.jpg
 Decoding (Extracting a Message)
python stego.py --decode -i encrypted.jpg
🔐 Future Enhancements
🔹 Least Significant Bit (LSB) Encoding for better security
🔹 AES Encryption before encoding
🔹 Support for Video Steganography
🔹 GUI with Tkinter / PyQt
