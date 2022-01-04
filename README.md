# Cryptology
This repository contains various algorithms and protocols about cryptography, cryptanalysis and needed mathematics (Discrete mathematics and Number Theory)

## One Time Pad

Gets input a plaintext, then we generate a key with the same length. The ciphertext is produced by the simple proccess:
$$ c = m \oplus k, $$

the coputation is executed bit-by-bit. Getting the plaintext from the ciphertext can be achieved by XORing again with the key:

$$ m = c \oplus k $$
