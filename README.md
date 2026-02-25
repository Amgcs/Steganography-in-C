# Steganography-in-C
LSB Image Steganography project implemented in C
📌 Steganography in C

This project implements Image Steganography using the LSB (Least Significant Bit) technique in C.

🔐 Features

Encode secret text into BMP image

Decode hidden text from image

Supports 24-bit BMP images

Command-line based interface

🛠 Technologies Used

C Programming

File Handling

Bitwise Operations

Structures

How to Compile
gcc *.c -o stego

How to Encode
./stego -e input.bmp secret.txt output.bmp

How to Decode
./stego -d output.bmp
