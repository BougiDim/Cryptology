# Cryptology
This repository contains various algorithms and protocols about cryptography, cryptanalysis and needed mathematics (Discrete mathematics and Number Theory)

## One Time Pad

Gets input a plaintext, then we generate a key with the same length. The ciphertext is produced by the simple proccess:
<img src="https://latex.codecogs.com/gif.image?\dpi{150}&space;\bg_white&space;\inline&space;c&space;=&space;m&space;\oplus&space;k" title="\bg_white \inline c = m \oplus k" />

the coputation is executed bit-by-bit. Getting the plaintext from the ciphertext can be achieved by XORing again with the key:
<img src="https://latex.codecogs.com/gif.image?\dpi{150}&space;\bg_white&space;\inline&space;m&space;=&space;c&space;\oplus&space;k" title="\bg_white \inline m = c \oplus k" />
