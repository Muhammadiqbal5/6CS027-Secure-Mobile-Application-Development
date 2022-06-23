# C and CUDA Password Cracking
Both the C and CUDA program can crack an
encrypted 2 letter, 2 number password.
EncryptSHA512.c generates an encrypted
password.

# Compile commands

C password cracking

gcc Password_Cracking.c -pthread -Icrypt

CUDA password cracking

nvcc Password_Cracking.cu
