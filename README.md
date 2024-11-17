# Caesar Cipher Encryption/Decryption Tool

This is a simple Python implementation of the Caesar Cipher, a basic encryption algorithm. The tool allows you to encrypt and decrypt messages by shifting the letters of the alphabet by a specified number. Non-alphabetic characters (such as spaces and punctuation) are left unchanged.

## Features
- **Encrypt**: Encrypt your message by shifting the letters of the alphabet by a specified value.
- **Decrypt**: Decrypt an encrypted message by reversing the shift applied during encryption.
- **Shift Range**: The shift value can be any integer between 1 and 25.

## How It Works
The Caesar Cipher works by shifting each letter in the message by a specified number of positions in the alphabet. For example, with a shift of 3:
- 'A' becomes 'D'
- 'B' becomes 'E'
- 'Z' wraps around to 'C'

This program allows you to:
- Encrypt a message by specifying a shift value.
- Decrypt a previously encrypted message using the same shift value.

### Example:
1. Encrypt the message: "Hello World" with a shift of 3:
   - "Hello World" becomes "Khoor Zruog".
   
2. Decrypt the message: "Khoor Zruog" with a shift of 3:
   - "Khoor Zruog" becomes "Hello World".

## Requirements
- Python 3.x

### No additional libraries are required for this tool.

## How to Use

1. **Run the Script**: To start the program, simply run the Python script. The program will prompt you to choose whether you'd like to encrypt or decrypt a message.

2. **Choose an Operation**:
   - Type **`e`** to encrypt a message.
   - Type **`d`** to decrypt a message.
   - Type **`q`** to quit the program.

3. **Enter the Message and Shift**:
   - After selecting the operation, you'll be prompted to enter the message you want to encrypt or decrypt.
   - Enter a shift value between 1 and 25 (inclusive). The shift determines how many positions the letters of the alphabet will be shifted.

4. **Result**: The program will display the encrypted or decrypted message.

### Example of Usage:
```bash
Would you like to (e)ncrypt or (d)ecrypt a message? (or 'q' to quit): e
Enter your message: Hello World
Enter the shift value (1-25): 3
Encrypted message: Khoor Zruog

Would you like to (e)ncrypt or (d)ecrypt a message? (or 'q' to quit): d
Enter your message: Khoor Zruog
Enter the shift value (1-25): 3
Decrypted message: Hello World
