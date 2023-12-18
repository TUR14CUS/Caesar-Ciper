# Caeser Cipher

## Overview
This Python script, `main.py`, implements a Caesar Cipher encryption and decryption tool. The Caesar Cipher is a simple substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet.

## Usage

1. Run the script by executing `python main.py` in your terminal.
2. You will be prompted to choose between encryption ('encode') and decryption ('decode').
3. Enter the message you want to encrypt or decrypt when prompted.
4. Input the shift number, which determines the amount of the shift in the alphabet.
5. The program will display the result of the encryption or decryption.

## Example

```
 ,adPPYba, ,adPPYYba,  ,adPPYba, ,adPPYba, ,adPPYYba, 8b,dPPYba,  
a8"     "" ""     `Y8 a8P_____88 I8[    "" ""     `Y8 88P'   "Y8  
8b         ,adPPPPP88 8PP"""""""  `"Y8ba,  ,adPPPPP88 88          
"8a,   ,aa 88,    ,88 "8b,   ,aa aa    ]8I 88,    ,88 88          
 `"Ybbd8"' `"8bbdP"Y8  `"Ybbd8"' `"YbbdP"' `"8bbdP"Y8 88   
            88             88                                 
           ""             88                                 
                          88                                 
 ,adPPYba, 88 8b,dPPYba,  88,dPPYba,   ,adPPYba, 8b,dPPYba,  
a8"     "" 88 88P'    "8a 88P'    "8a a8P_____88 88P'   "Y8  
8b         88 88       d8 88       88 8PP""""""" 88          
"8a,   ,aa 88 88b,   ,a8" 88       88 "8b,   ,aa 88          
 `"Ybbd8"' 88 88`YbbdP"'  88       88  `"Ybbd8"' 88          
              88                                             
              88           
"""

Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello
Type the shift number:
3
Here's the encoded result: khoor
Type 'yes' if you want to go again. Otherwise type 'no'.
yes

...

Goodbye
```

## Notes

- The script uses the provided `alphabet` list for valid characters.
- The `art` module is imported to display the script's logo.
- You can exit the program by typing 'no' when prompted to restart.

Feel free to use and modify this script for your own purposes. If you have any questions or suggestions, please reach out to the project contributors.
