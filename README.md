# Steganography-using-C

**Project Summary**

This project is a C-based steganography application that hides secret files inside BMP images using the Least Significant Bit (LSB) technique. The system takes a cover image and a secret file, checks whether the image has enough capacity, and embeds the hidden data into the least significant bits of the image pixels while preserving the original image structure. It stores metadata such as the magic identifier, secret file extension, and file size before embedding the actual secret content. On the decoding side, the program reads the stego image, extracts the hidden data, reconstructs the original file, and saves it as a new output file.

The project demonstrates how digital watermarking/steganography works in practice, combining file handling, bitmap structure analysis, binary data manipulation, and C programming. It is useful as a mini-project for understanding secure data hiding, image processing, and information embedding without visibly changing the image.


**Topics covered**
Steganography
LSB (Least Significant Bit) encoding and decoding
BMP image file handling
Bit-level data manipulation
C programming concepts like file I/O, pointers, structures, and memory management
Data hiding and extraction techniques

**Learning progress**

Learned how data can be hidden inside an image without changing its visible appearance.
Improved understanding of binary data, bit operations, and file structure.
Gained practical experience in C programming and using image files in software projects.
Understood the importance of checking file capacity, metadata, and validation before hiding data.
Developed problem-solving skills by working with encoding, decoding, and debugging steganography logic.

This project helped me connect theory with practical implementation and improved my understanding of digital data hiding and image processing.
