# Cipher Encryptor/Decryptor - Python

## Description
This Python program uses a basic substitution cipher to encrypt and decrypt messages. The program first creates a random key by shuffling a list of characters, which it uses to substitute each character in the input message with another character. This key is used both for encrypting and decrypting.

## Features
- **Random Key Generation**: Generates a shuffled key based on a list of all whitespace, punctuation, digits, and ASCII letters.
- **Encryption**: Substitutes each character in the original message with a character from the shuffled key, creating an encrypted message.
- **Decryption**: Substitutes each character in the encrypted message back to its original form using the shuffled key.

## How to Use
1. **Clone or download** this repository to your local machine.
2. **Run the program** in a Python environment.
3. **Follow the prompts**:
   - **Encrypting a Message**: Enter a message you want to encrypt. The program will display the original and encrypted messages.
   - **Decrypting a Message**: Enter the encrypted message to decrypt it back to the original text.

## Example Usage
```bash
Enter a message to Encrypt: Hello, World!
Original message: Hello, World!
Encrypted message: fC-@#,28@_H>

Enter a message to Decrypt: fC-@#,28@_H>
Encrypted message: fC-@#,28@_H>
Original message: Hello, World!
