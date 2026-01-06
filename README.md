# Discrete-Mathematics
# Cryptography Suite in C++

Welcome to the **Cryptography Suite in C++**! This is a simple, console-based program designed to help you explore and understand the basics of cryptography. With this project, you can encrypt and decrypt messages using three popular methods: **Caesar Cipher**, **Affine Cipher**, and **RSA encryption**. It’s a great way to learn how letters and numbers can be transformed into secret codes and back again.

## What This Project Does
The program lets you:
- Shift letters using the **Caesar Cipher**, where each letter moves forward or backward by a fixed number.
- Apply the **Affine Cipher**, which uses a mathematical formula to scramble letters in a more complex way.
- Use **RSA encryption**, a real-world public-key system, to securely encrypt messages in blocks.

It also ensures that the inputs are valid, like checking numbers for keys or keeping non-letter characters intact in your messages.

## How to Get Started
1. Download or clone the project to your computer.
2. Open it in your favorite C++ IDE or compiler, such as Code::Blocks, Dev-C++, or Visual Studio.
3. Compile the project. For example, in the terminal you can run:
   ```bash
   g++ cryptography.cpp -o cryptography

Usage Examples
Caesar Cipher

Encrypt:

Enter a String to Encrypt: HELLO
Enter K: 3
Output: KHOOR


Decrypt:

Enter a String to Decrypt: KHOOR
Enter K: 3
Output: HELLO

Affine Cipher

Encrypt:

Enter a String to Encrypt: HELLO
Enter a: 5
Enter b: 8
Output: RCLLA


Decrypt:

Enter a String to Decrypt: RCLLA
Enter a: 5
Enter b: 8
Output: HELLO


Note: a must be coprime with 26 (e.g., 1,3,5,7,9,...,25)

RSA Cipher

Encrypt:

Enter prime p: 7
Enter prime q: 11
Enter public key e: 17
Enter plaintext (CAPITAL LETTERS ONLY): HELLO
Output: Encrypted Blocks: 89 56 12


Decrypt:

Enter number of cipher blocks: 3
Enter cipher block 1: 89
Enter cipher block 2: 56
Enter cipher block 3: 12
Output: HELLO

Dependencies:

Standard C++ libraries:

<iostream> for input/output

<string> for string manipulation

<cmath> for mathematical operations (used for modular arithmetic)

No external libraries are required.
