# Python-Ceaser-Cipher
The Caesar cipher is a simple encryption technique used to protect messages, named after Julius Caesar. It involves shifting the letters of the plaintext message by a fixed number of positions. Despite its simplicity, the Caesar cipher formed the groundwork for modern cryptographic techniques.

Key Features

a) The Caesar cipher is a substitution cipher, where each letter in the plaintext is replaced by a letter with a fixed number of positions down the alphabet. 
The encryption can be represented using modular arithmetic by transforming the letters into numbers (A=0, B=1, ..., Z=25) and applying the formula En(x) = (x + n) mod 26. 

b) The Caesar cipher is easy to implement, requires only a small set of pre-shared information, and can be physically implemented. 
However, it is not secure against modern decryption methods, is vulnerable to known-plaintext attacks, and has a limited keyspace (only 26 possible keys), making it vulnerable to brute-force attacks. 
