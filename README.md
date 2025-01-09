
# Huffman Tree Project

This project implements a **Huffman Tree** in C for efficient data compression. It is a comprehensive implementation of the Huffman Coding algorithm, which is used to generate optimal prefix codes based on character frequencies.

---

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Project Structure](#project-structure)
- [Example Usage](#example-usage)
---

## About the Project
The Huffman Tree project provides a complete pipeline for compressing and decompressing files using Huffman coding. The implementation includes reading file data, calculating character frequencies, building the Huffman tree, and encoding/decoding the data.

### Key Features:
- **Compression**: Encodes data into a compressed binary format.
- **Decompression**: Restores original data from the compressed format.
- **Huffman Codes Generation**: Produces a `.cod` file containing character mappings and codes.
- **Binary Representation**: Prints the compressed data as binary.
- **Interactive Menu**: Allows users to generate codes, compress files, or decompress files.

---

## Features
- Complete implementation of Huffman coding in C.
- Generates `.cod` files with Huffman codes for input data.
- Compresses data into a `.com` file format.
- Decompresses `.com` files back to their original content.
- Provides a menu-based interface for easy interaction.

---

## Technologies Used
- **Programming Language**: C
- **Standard Libraries**: stdio.h, stdlib.h, string.h, stdbool.h
- **Compiler**: GCC or any compatible C compiler

---

## How to Run
### Prerequisites:
- Install a C compiler (e.g., GCC).
- Set up a command-line environment (Linux, macOS, or Windows).

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/Hazem-ElKanawati/HuffmanTree.git
   ```
2. Navigate to the project directory:
   ```bash
   cd HuffmanTree
   ```
3. Compile the program:
   ```bash
   gcc Source.cpp -o HuffmanTree
   ```
4. Run the program:
   ```bash
   ./HuffmanTree
   ```

---

## Project Structure
```plaintext
HuffmanTree/
│
├── Source.cpp          # Main source code for the project
├── README.md           # Documentation
└── LICENSE             # Licensing information
```

---

## Example Usage

### Generating Huffman Codes
1. Input a text file (e.g., `example.txt`).
2. The program generates a `.cod` file with Huffman codes.

### Compressing a File
1. Use the `.cod` file to compress the original file into a `.com` format.

### Decompressing a File
1. Use the `.com` file and the `.cod` file to restore the original file.

### Example Menu Interaction:
```plaintext
Menu:
1. Generate Huffman codes and print to terminal
2. Compress a file
3. Decompress a file
4. Exit
Enter your choice: 1

Enter the input filename: example.txt
.cod file generated successfully.
Huffman Codes:
a : 101
b : 110
c : 111
...
```
