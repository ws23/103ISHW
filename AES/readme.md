# Homework
# A Modified XTS-AES Encryption and Decryption
## Input File: input.exe and key.txt
## Time Limit: No

### Problem Description
Advanced Encryption Standard (AWS) is a well-known synnetric block cipher in modern crytography. It was published by NIST in 2001. Here, we design a modified XTS-AES as shown in Fig.1. Please write rwo programs for encryption and decryption (e.g., encrypt.cpp and decrypt.cpp). To test the correctness of your encryption and decryption, two samples (one 256-bit plaintext and one 192-bit plaintext) with 128-bit Key1 and 128-bit Key2 (please see Input File in Hex format), and 256-bit ciphertext and 192-bit ciphertext (please see Output File in Hex format) are given. Notice that, in your program, please use the value (i+1) for counter i, i.e., the values of counter 0 and counter 1 are 1 and 2, respectively, for the test samples. 

### Input File Format
There are two input files: one is input.txt (the paintextr or ciphertext) for encryption and decryption, and the other is ket.txt to store modified XTS-AES\'s key. The input.txt contains n-bit with Hex format. Also, the first line (respectively, second line) in key.txt is 128-bit Key1 (respectively, Key2) with Hex format. 

### Out
