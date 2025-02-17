# caesar-cipher-implementation-using-python

### Definition of Caesar Cipher

The Caesar Cipher is a simple and widely known substitution cipher used in cryptography. It shifts each letter in the plaintext by a fixed number of positions in the alphabet. For example, with a shift of 3, `A` becomes `D`, `B` becomes `E`, and so on.  
# Mathematical Representation: 
For each letter x in the plaintext, the encrypted letter E(x) is:  

E(x) = (x + n) \mod 26

Where n is the shift value and 26 is the total number of letters in the English alphabet.  

# Example (Shift = 3): 
 Plaintext: `HELLO`
 shift key: `3` 
 Ciphertext: `KHOOR`  

The Caesar Cipher is easy to break using frequency analysis and brute-force attacks but serves as the foundation for more complex encryption methods.  
