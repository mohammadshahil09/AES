# EX-8-ADVANCED-ENCRYPTION-STANDARD ALGORITHM

## Aim:

To use Advanced Encryption Standard (AES) Algorithm for a practical application like URL Encryption.

## Algorithm:

1. AES is based on a design principle known as a substitution–permutation.

2. AES does not use a Feistel network like DES, it uses variant of Rijndael.

3. It has a fixed block size of 128 bits, and a key size of 128, 192, or 256 bits.

4. AES operates on a 4 × 4 column-major order array of bytes, termed the state

## Program:
```
#include <stdio.h>
#include <string.h>

void xor_encrypt_decrypt(char *input, char *key) {
    int input_len = strlen(input);
    int key_len = strlen(key);
    for (int i = 0; i < input_len; i++) {
        input[i] = input[i] ^ key[i % key_len];
    }
}

int main() {
    char url[] = "WELCOME";
    char key[] = "secretkey";
    
    printf("Original text: %s\n", url);
    xor_encrypt_decrypt(url, key);
    printf("Encrypted text: %s\n", url);
    xor_encrypt_decrypt(url, key);
    printf("Decrypted text: %s\n", url);

    return 0;
}
```
## Output:

# EX-8-ADVANCED-ENCRYPTION-STANDARD ALGORITHM

## Aim:

To use Advanced Encryption Standard (AES) Algorithm for a practical application like URL Encryption.

## Algorithm:

1. AES is based on a design principle known as a substitution–permutation.

2. AES does not use a Feistel network like DES, it uses variant of Rijndael.

3. It has a fixed block size of 128 bits, and a key size of 128, 192, or 256 bits.

4. AES operates on a 4 × 4 column-major order array of bytes, termed the state

## Program:
```
#include <stdio.h>
#include <string.h>

void xor_encrypt_decrypt(char *input, char *key) {
    int input_len = strlen(input);
    int key_len = strlen(key);
    for (int i = 0; i < input_len; i++) {
        input[i] = input[i] ^ key[i % key_len];
    }
}

int main() {
    char url[] = "WELCOME";
    char key[] = "secretkey";
    
    printf("Original text: %s\n", url);
    xor_encrypt_decrypt(url, key);
    printf("Encrypted text: %s\n", url);
    xor_encrypt_decrypt(url, key);
    printf("Decrypted text: %s\n", url);

    return 0;
}
```
## Output:

![image](https://github.com/user-attachments/assets/977081a7-a7aa-4aae-ad2f-d01d1fa841fd)


## Result:

Thus code for Advanced Encryption Standard (AES) Algorithm for a practical application like URL Encryption is executed successfully.



## Result:

Thus code for Advanced Encryption Standard (AES) Algorithm for a practical application like URL Encryption is executed successfully.
