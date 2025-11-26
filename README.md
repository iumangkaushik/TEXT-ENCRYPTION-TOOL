---

# 🔐 Multi-Algorithm Text Encryption Utility (Python)

This Python utility enables you to **encrypt and decrypt text** using three distinct encryption methods: **AES**, **DES**, and **RSA**. It showcases both symmetric and asymmetric encryption techniques through a simple command-line interface.

## 🛠️ Capabilities

* **AES Encryption**: Implements AES in CBC mode with randomly generated keys.
* **DES Encryption**: Uses DES in ECB mode with randomly generated keys.
* **RSA Encryption**: Employs a 2048-bit RSA key pair for secure encryption and decryption.
* Supports encrypting and decrypting any text using these three algorithms.

## 🚀 Setup Instructions

### Requirements:

Make sure Python 3.x is installed on your system. Additionally, you need the following Python packages:

* `pycryptodome` for AES and DES encryption
* `rsa` for RSA encryption
* `colorama` for colorful console outputs

Install all dependencies via pip:

```bash
pip install pycryptodome rsa colorama
```

---