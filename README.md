# Enigma
> Enigma is an encryption/decryption program that writes or decrypts messages onto a .txt file

- [Features](#features)
- [How to Use](#how-to-use)
- [Usage Examples](#usage-examples)
- [Contributors](#contributors)
- [How to Contribute](#how-to-contribute)

## Features

**Enigma** reads a message using File.IO and encrypts it to another file. This process can be reversed using the same files using a *key* and a *date*.

## How to Use

A user can write their message in the `message.txt` file in the root directory. They are then able to encrypt/decrypt message like so:

Encryption
```
$ ruby ./lib/encrypt.rb message.txt encrypted.txt
Created 'encrypted.txt' with the key 82648 and date 240818
```
Decryption
```
$ ruby ./lib/decrypt.rb encrypted.txt decrypted.txt 82648 240818
Created 'decrypted.txt' with the key 82648 and date 240818
```

## Usage Examples

Algorithm-Based Encryption/Decryption

[![Screen-Shot-2021-09-18-at-12-49-48-PM.png](https://i.postimg.cc/25MDn2Zq/Screen-Shot-2021-09-18-at-12-49-48-PM.png)](https://postimg.cc/xkvh2GgY)


Encryption Example

[![Screen-Shot-2021-09-18-at-12-50-55-PM.png](https://i.postimg.cc/9XS7rh0V/Screen-Shot-2021-09-18-at-12-50-55-PM.png)](https://postimg.cc/s1YXNb50)


Decrypted Message

[![Screen-Shot-2021-09-18-at-12-51-05-PM.png](https://i.postimg.cc/J7bs4Bf3/Screen-Shot-2021-09-18-at-12-51-05-PM.png)](https://postimg.cc/NLjsdLfL)

*-Voltaire*


## Contributors

👤  **Matt Kragen**
- [GitHub](https://github.com/matt-kragen)
- [LinkedIn](https://www.linkedin.com/in/mattkragen/)

## How to Contribute

1. Fork it (<https://github.com/matt-kragen/enigma/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request
