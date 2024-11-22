# Random-Interval-Encryption-and-Decryption
This repository contains a Python implementation of a simple encryption and decryption program. The script takes user input, encrypts it using a randomly generated interval, and then allows decryption of the encrypted message using the same interval.

Features
Randomized Encryption:
Generates a random interval (between 2 and 20).
Inserts random characters between the actual message characters based on the interval.
Decryption:
Retrieves the original message using the same interval used during encryption.
How It Works
The user inputs a message to be encrypted.
The program generates a random interval and encrypts the message by inserting random letters between each character of the original message.
The program can then decrypt the message by skipping over the random letters using the interval.
Example
Input: hello
Encrypted Output: hxazltxyzziqwoxprylom (varies due to randomization)
Decrypted Output: hello
Requirements
Python 3.x
No external libraries required; the script uses Python's built-in random and string modules.
