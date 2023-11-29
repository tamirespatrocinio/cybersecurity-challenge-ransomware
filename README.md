# Ransomware - Bootcamp Challenge

This project involves the implementation of a simple ransomware using the Python programming language. Please note that the purpose of this project is purely educational, and it is essential to use this knowledge responsibly and legally.

## Step-by-Step Guide

### 1. Clone the Repository
Clone this repository to your local machine to get started.

```bash
git clone https://github.com/tamirespatrocinio/cybersecurity-challenge-ransomware.git
cd cybersecurity-challenge-ransomware
```

### 2. Encryption Script (encrypter.py)
The `encrypter.py` script is responsible for encrypting a target file (`teste.txt` in this example) and appending the extension ".ransomwaretroll" to the encrypted file.

```bash
python encrypter.py teste.txt
```

This command will create a file named `teste.txt.ransomwaretroll` in the same directory.

![VirtualBox_01](https://github.com/tamirespatrocinio/cybersecurity-challenge-ransomware/assets/73259410/f9f455a0-1c5d-4080-b534-5ae26ffd1435)
![VirtualBox_02](https://github.com/tamirespatrocinio/cybersecurity-challenge-ransomware/assets/73259410/ff04e683-55f9-4fc6-91ab-52cd1ed00c5c)

### 3. Decryption Script (decrypter.py)
The `decrypter.py` script reverses the encryption process, taking the encrypted file (`teste.txt.ransomwaretroll`) and restoring it to its original state (`teste.txt`).

```bash
python decrypter.py teste.txt.ransomwaretroll
```

After running this command, you should find the decrypted file (`teste.txt`) in the same directory.

![VirtualBox_03](https://github.com/tamirespatrocinio/cybersecurity-challenge-ransomware/assets/73259410/6120e90c-aaa4-4679-a76b-586dbcc9eff8)
![VirtualBox_04](https://github.com/tamirespatrocinio/cybersecurity-challenge-ransomware/assets/73259410/dce2a27b-4c27-4bb3-9a7b-9b542d415471)

### Important Notes
- Do not use this code for any malicious purposes. This project is for educational purposes only.
- Always comply with legal and ethical standards when working with security-related projects.
- Use this knowledge responsibly and do not engage in any illegal activities.

### Disclaimer
The author and contributors are not responsible for any misuse or damage caused by the implementation of this ransomware. Use it at your own risk and only in a controlled environment for educational purposes.

## Contributing
Feel free to contribute to this project by creating pull requests. However, please ensure that your contributions align with the ethical use of knowledge and adhere to legal standards.
