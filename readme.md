# Vigenere Cipher

This folder contains a C implementation of the Vigenere cipher, a polyalphabetic substitution cipher that uses a keyword to encrypt and decrypt messages. It is more secure than a simple Caesar cipher because it uses multiple Caesar ciphers with different shift values.

## Usage

To use the Vigenere cipher, follow these steps:

1. **Set File**: Use the `Set file` option to specify the plaintext file you want to encrypt or decrypt.

2. **Encrypt**: Use the `Encrypt` option to encrypt the plaintext file using a specified key. The encrypted text will be displayed and saved in a file named `encryptedtext.txt`.

3. **Decrypt**: Use the `Decrypt` option to decrypt the encrypted text using the same key. The decrypted text will be displayed.

4. **Vigenere Analysis**: Use the `Vigenere Analysis` option to perform analysis on the encrypted text. This includes:
   - **IOC Analysis**: Index of Coincidence analysis.
   - **Kasiski Analysis**: Determines the key length.
   - **Predict Key**: Predicts the key used for encryption.

5. **Exit**: Use the `Exit` option to exit the program.

## Dependencies

This program requires the following dependencies:

- `ctype.h`: Functions for character classification and conversion.
- `string.h`: Functions for string manipulation.
- `stdio.h`: Functions for file input/output.
- `stdlib.h`: Functions for memory allocation and deallocation.

## Compilation

To compile the program, use the following command:

```bash
gcc main.c -o vigenere
```

## Running the Program

To run the program, use the following command:

```bash
./vigenere
```

## Menu Options

Upon running the executable, you will be presented with a menu of options:

```
Options:
1. Set file
2. Encrypt
3. Decrypt
4. Vigenere Analysis
5. Exit
------------------------
File: Not Set | Key: Not Set

Enter your choice:
```

### Notes

- Ensure the plaintext file exists in the same directory as the executable or provide the full path to the file.
- The key should only contain alphabetic characters.

## Options Detail

- **Set File**: Enter the filename of the plaintext file you want to encrypt.
- **Encrypt**: Enter the key for encryption. The encrypted text will be displayed and saved in `encryptedtext.txt`.
- **Decrypt**: Enter the key for decryption. The decrypted text will be displayed.
- **Vigenere Analysis**: Choose from the following analysis options:
    - **IOC Analysis**: Computes the Index of Coincidence.
    - **Kasiski Analysis**: Determines the possible key length and patterns.
    - **Predict Key**: Attempts to predict the encryption key.
- **Exit**: Exit the program.



## Group Members
- Parth Gupta (2210110452)
- Preyanshe Jindal (2210110479)
- Purva Batra (2210110485)
