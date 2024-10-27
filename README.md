# Secure Messaging Application using NTRU and Salsa20

## Project Overview

This project is a Python-based secure messaging application that uses post-quantum encryption techniques to facilitate private communication between clients over a central server. The server acts solely as a message-forwarding node, ensuring that messages remain private and secure from eavesdropping, even on the server itself.

### Technologies and Cryptographic Techniques

This application leverages the following cryptographic protocols and algorithms for secure communication:

- **NTRU (N-th Degree Truncated Polynomial Ring Units)**: A post-quantum public-key encryption algorithm used for secure key exchange. NTRU ensures that the shared secret established between clients remains secure against potential quantum computing attacks.
  
- **Salsa20**: A fast and secure stream cipher used for encrypting messages after a shared secret is established. Salsa20 provides high-speed encryption and is well-suited for real-time messaging applications.
  
- **Ed25519**: A digital signature algorithm used to sign messages, guaranteeing message integrity and authenticity. Ed25519 ensures that any message tampering is detectable by the recipient.
