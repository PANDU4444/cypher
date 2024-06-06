# Cryptography Ciphers

This notebook contains Python implementations of various cryptography ciphers. These ciphers can be used to encrypt and decrypt text.

## Ciphers Included

1. Affine Cipher
2. Atbash Cipher
3. Baconian Cipher
4. Base64
5. Bifid Cipher

## Usage

To use this notebook:
1. Run each code cell sequentially.
2. Follow the instructions provided to select a cipher, enter the text, and choose whether to encrypt or decrypt.

### Affine Cipher

The Affine Cipher is a type of monoalphabetic substitution cipher, where each letter in an alphabet is mapped to its numeric equivalent, encrypted using a simple mathematical function, and converted back to a letter. It uses the mathematical formula \(E(x) = (ax + b) \mod m\), where \(x\) is the letter to be encrypted, \(a\) and \(b\) are the keys of the cipher, and \(m\) is the size of the alphabet.

### Atbash Cipher

The Atbash Cipher is a substitution cipher where the alphabet is reversed. For example, A becomes Z, B becomes Y, and so on. It was originally used for the Hebrew alphabet but can be adapted for any alphabet.

### Baconian Cipher

The Baconian Cipher is a substitution cipher in which each letter is replaced by a group of five characters, usually 'A' and 'B'. This cipher is named after Sir Francis Bacon. It can encode spaces and punctuation, making it more flexible than some other ciphers.

### Base64

Base64 is a method for encoding binary data into an ASCII string format. It is commonly used to encode binary data in email messages, attachments, and other ASCII or text-based communication protocols. Base64 is commonly used in cryptography to encode binary data in a format that can be easily transmitted over communication protocols that can only handle text.

### Bifid Cipher

The Bifid Cipher is a combination of the Polybius square and the transposition cipher. It uses a 5x5 grid to encode pairs of plaintext characters. It was invented by Felix Delastelle in 1901.

## Credits

This notebook was created by [Your Name].

