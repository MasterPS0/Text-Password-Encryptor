# Text Password Encryptor

A simple offline HTML tool that allows users to encrypt and decrypt text using a password.

## Features

- Encrypt text with a password
- Decrypt text with the same password
- AES-GCM 256-bit encryption
- Works completely offline
- No server required
- Modern and responsive interface
- Copy output to clipboard
- Clear input and output fields

## Usage

### Encrypt Text

1. Open `index.html`
2. Enter text in the **Input Text** field
3. Enter a password
4. Click **Encrypt**
5. Copy the encrypted result from the **Output** field

### Decrypt Text

1. Paste encrypted text into the **Input Text** field
2. Enter the correct password
3. Click **Decrypt**
4. The original text will appear in the **Output** field

## Security

This tool uses:

- AES-GCM encryption
- 256-bit key strength
- Browser Web Crypto API

All encryption and decryption operations are performed locally in your browser.

No data is uploaded or transmitted over the Internet.

## Requirements

Supported browsers:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

## Project Files

```text
index.html
README.md
```

## Notes

- The same password must be used for encryption and decryption.
- If an incorrect password is entered, decryption will fail.
- Lost passwords cannot be recovered.

## Version

Version: 1.0

## License

Free to use for personal and educational purposes.

## Author

Text Password Encryptor
Offline HTML Encryption Tool
