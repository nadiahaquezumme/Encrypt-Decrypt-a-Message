# Secure Message Encryption & Signature
This project demonstrates a complete secure communication workflow using Python — including message encryption, decryption, and digital signatures to ensure authenticity and integrity.
It was developed as part of a collaborative assignment, where each partner encrypts their own message and decrypts the other partner’s message using shared cryptographic keys.

Key Features
Asymmetric Encryption (Public/Private Keys):
Uses RSA to securely encrypt messages so only the intended receiver can decrypt them.

Digital Signature Generation:
Creates a unique signature for each message to verify the sender’s identity.

Signature Verification:
Confirms that the message was not altered and truly came from the sender.

Python-Based Implementation:
Built using Python libraries such as cryptography (or PyCrypto) for real-world-grade security.

Partner Collaboration:
Each partner:

Encrypts their own message

Signs the message

Sends the encrypted text + signature

Decrypts and verifies the partner's message

How It Works

Key Generation:
Each user generates their own RSA key pair (private + public).

Message Encryption:
Sender encrypts the message using the receiver’s public key.

Digital Signing:
Sender signs the original plaintext using their private key.

Transmission:
Sender shares:
Encrypted message
Digital signature

Decryption & Verification:
Receiver uses:
Their private key to decrypt
Sender’s public key to verify the signature

Purpose of the Project
To understand real-life cryptographic workflows
To implement secure communication in Python
To practice key management, encryption algorithms, and signature methods
To simulate secure data exchange between two parties
