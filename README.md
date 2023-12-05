## vigenere-bit-xor

a simple bit-based vigenere cipher using XOR function


### Program Explained.

 - Create a ***repeatResult*** variable that contains the repeated key so that its length matches the length of the ***plaintext***.
   ![Screenshot 2023-12-05 175234](https://github.com/ilhamyulianto/vigenere-bit-xor/assets/96160369/d93ee377-7819-4322-aabd-cebc0b7466b5)
   
 - Converts **plaintext** and keys into binary representation using **8-bit** format.
   ![Screenshot 2023-12-05 175453](https://github.com/ilhamyulianto/vigenere-bit-xor/assets/96160369/d40f2cc1-18ab-45b6-a753-3be680c31c2c)

 - Performs an ***XOR*** operation on each plaintext bit and key for encryption, and on each ciphertext bit and key for decryption.
   ![image](https://github.com/ilhamyulianto/vigenere-bit-xor/assets/96160369/78e968be-c98c-414f-9765-f9ae62afbfa9)

 - Breaks the decryption result into **8-bit** blocks and converts each block back into ***ASCII*** characters.
   ![image](https://github.com/ilhamyulianto/vigenere-bit-xor/assets/96160369/38c2ba42-7718-4f42-8901-444481514008)


### Importan to know!
- **Repeat Key**: This method is similar to the way the key is repeated in the Vigenere Cipher method. This ensures that each plaintext character has a corresponding key to operate on.
- ***XOR* operation**: The use of *XOR* operation is the essence of encryption and decryption. Each bit operates with the corresponding bit of the key, producing results that are difficult to decipher without the correct key.
- **Binary and *ASCII* Representation**: Conversion between binary and *ASCII* representation is required to convert text to and from a representation that can be operated on using the *XOR* operation.
- **Additional Information**: Additional output such as binary representation of the plaintext and key helps in understanding how the *XOR* operation is performed at the bit level.

## How to run.

just simply run `'python vigenere-xor.py'`  on terminal or command prompt.

