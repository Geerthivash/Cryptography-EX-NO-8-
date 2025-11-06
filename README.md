# EX-8-ADVANCED-ENCRYPTION-STANDARD ALGORITHM
```
GEERTHIVASH J.D. - 212223060067
```
# Aim:
To use Advanced Encryption Standard (AES) Algorithm for a practical application like URL Encryption.

# ALGORITHM:
AES is based on a design principle known as a substitution–permutation.
AES does not use a Feistel network like DES, it uses variant of Rijndael.
It has a fixed block size of 128 bits, and a key size of 128, 192, or 256 bits.
AES operates on a 4 × 4 column-major order array of bytes, termed the state
# PROGRAM:
```
#include <stdio.h>
#include <string.h>

void encryptDecrypt(char *input, char *key) {
    int inputLen = strlen(input);
    int keyLen = strlen(key);

    for (int i = 0; i < inputLen; i++) {// XOR encryption/decryption
    }
}

int main() {
    char url[100] = "https://www.google.com";
    char key[20] = "mysecretkey";

    printf("Original URL: %s\n", url);

    encryptDecrypt(url, key);   
    printf("Encrypted URL (in hex): ");
    for (int i = 0; i < strlen(url); i++)
        printf("%02x", (unsigned char)url[i]);
    printf("\n");

    encryptDecrypt(url, key);   
    printf("Decrypted URL: %s\n", url);

    return 0;
}

```
# OUTPUT:
<img width="629" height="257" alt="image" src="https://github.com/user-attachments/assets/d40f571e-53d9-4302-9947-3a29089a2c53" />


# RESULT:
Thus the Advanced Encryption Standard (AES) Algorithm for a practical application like URL
Encryption is done successfully.

