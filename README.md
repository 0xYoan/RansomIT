# RansomIT

> Encrypt files with keys generated by ED25519 algorithm.

[![LICENSE][license-image]][license-url]

## Introduction

This project was developed during my internship in cybersecurity. The goal was to make a simple python ransomware to test its propagation in a cloud environment. The RansomIT program encrypts files using a key pair generated with the ED25519 algorithm.

## Installation

OS X & Linux & Windows:

```python
git clone https://github.com/0xYoan/RansomIT.git
cd RansomIT
pip3 install -r requirements.txt
```

## Usage

### Encryption

1. Open code and change **TARGET_PATH** constant. This is the starting point of the encryption. *`BE CAREFUL WITH THIS, IT CAN CAUSE DAMAGE TO YOUR SYSTEM !`*

2. Simply run the code : `python3 RansomIT.py`.
3. Copy generated ID somewhere to decrypt files later.
4. All done !

Example of ID:

```plaintext
Your ID : e28b951c-5f1d-45fd-93a4-648007bc5066
```

### Decryption

1. Open code and change **TARGET_PATH** constant. This is the starting point of the decryption.

2. Simply run the code : `python3 DeRansomIT.py`.
3. Paste ID to decrypt files.
4. All done !

## TODO

- Add multithreading
- Manage keys with VPS and SFTP
- Test on other platforms
- More features...

## Meta

Author : Yoan Ancelly

![Twitter Follow](https://img.shields.io/twitter/follow/0xYoan?style=social)

Distributed under the GNU GPLv3 license. See ``LICENSE`` for more information.


## Contributing

1. Fork it (<https://github.com/0xYoan/RansomIT/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[license-image]: https://img.shields.io/github/license/0xYoan/RansomIT
[license-url]: https://www.gnu.org/licenses/gpl-3.0.en.html

## Disclaimer

> This tool is only for testing and academic purposes and can only be used where strict consent has been given. Do not use it for illegal purposes! It is the end user’s responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this tool and software in general.
