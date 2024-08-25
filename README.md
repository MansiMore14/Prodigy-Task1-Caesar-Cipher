Project Title: Caesar Cipher.

Description: The Caesar Cipher Encryption and Decryption Utility is a Python-based application that facilitates the encryption and decryption of text utilizing the Caesar Cipher algorithm. This method is a simple substitution cipher in which each letter in the plaintext is shifted a designated number of positions either forward or backward in the alphabet.

Features:

Encryption: Users can enter a message and specify a shift value (an integer) to encrypt the text. The application shifts each letter by the indicated number of positions, wrapping around the alphabet as needed, and produces the encrypted output.

Decryption: Users can provide an encrypted message along with the shift value that was applied during encryption to retrieve the original text. The application reverses the encryption by shifting each letter in the opposite direction to uncover the initial plaintext.

Input Validation: The application verifies that user inputs consist solely of alphabetic characters and that the shift value is an integer.

User-Friendly Interface: The utility features an intuitive command-line interface (CLI) that allows users to choose between encryption and decryption, input messages, and specify shift values interactively.

Case Preservation: The application retains the case of letters in the message. Uppercase letters are encrypted as uppercase, while lowercase letters are encrypted as lowercase.

Error Handling: The program manages invalid inputs effectively, providing clear error messages to guide users in correcting their entries.

Usage:

1. Execute the program.
2. Select either encryption ('E') or decryption ('D').
3. Input the message to be encrypted or decrypted.
4. Indicate the shift value (an integer).
5. The application will present the encrypted or decrypted message.

