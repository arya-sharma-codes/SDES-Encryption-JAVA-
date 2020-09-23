# SDES-Encryption-JAVA-
TCN 5080 Project 1

Group Members: 
Arya Sharma PID 6206553
Andres Sierra PID 6097346

Operating System: Windows 10

Programming Language: Java


Compiling Instructions
Command prompt, javac SDES.java


run the file
java SDES **Mode** **10 bit Key** **8 bit IV** **Plaintext File** **Ciphertext File**


Mode:
Type encrypt for encryption 
Type decrypt for decryption
code won't run of mode is invalid

Key:
Type 10 bit Key, ex 1010010001
Key needs to be 10 bit.

IV:
Type 8 bit IV, example 10101010
Iv needs to be 8 bit.

Plaintext File:
Type name of file containing plaintext, this is provided in the zip folder named file.txt

Ciphertext File:
Type name of File containing ciphertext, this is provided in the zip folder named cipher.txt


Use the following inputs: 

For Encryption
java SDES encrypt 1010010001 10101010 file.txt out.txt

For Decryption
java SDES decrypt 1010010001 10101010 outplain.txt cipher.txt
