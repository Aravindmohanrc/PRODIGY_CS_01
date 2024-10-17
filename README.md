Caesar Cipher Implementation
Encryption:
 * Input: Obtain the plaintext message and the shift value (key).
 * Shift: For each character in the plaintext, shift its position in the alphabet by the shift value. If the shifted position goes beyond the end of the alphabet, wrap around to the beginning.
 * Output: The resulting ciphertext.
Decryption:
 * Input: Obtain the ciphertext and the shift value (key).
 * Shift: For each character in the ciphertext, shift its position in the alphabet by the negative of the shift value. If the shifted position goes beyond the beginning of the alphabet, wrap around to the end.
 * Output: The original plaintext message.
Python Implementation:
