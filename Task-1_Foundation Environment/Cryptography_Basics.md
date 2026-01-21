# Cryptography Basics

Cryptography is the practice of securing information by transforming it
into a format that is unreadable to unauthorized users. In cybersecurity,
cryptography is used to protect data confidentiality, maintain integrity,
and verify authenticity of communication.

---

## Encryption

Encryption converts plain text into cipher text to prevent unauthorized
access.

### Types of Encryption

- **Symmetric Encryption**
  - Uses the same key for encryption and decryption
  - Faster and efficient for large data
  - Example algorithms: AES, DES

- **Asymmetric Encryption**
  - Uses a pair of keys: public key and private key
  - More secure for key exchange
  - Example algorithms: RSA, ECC

Encryption ensures that even if data is intercepted, it cannot be read
without the correct key.

---

## Hashing

Hashing is a one-way cryptographic function used to convert data into a
fixed-length value called a hash.

### Key Characteristics of Hashing
- One-way (cannot be reversed)
- Same input always produces the same hash
- Small changes in input produce different hashes

### Common Hashing Algorithms
- MD5
- SHA-1
- SHA-256

Hashing is commonly used for password storage and data integrity
verification.

---

## Digital Certificates and SSL/TLS

SSL (Secure Sockets Layer) and TLS (Transport Layer Security) are
cryptographic protocols used to secure communication over networks.

### Purpose of SSL/TLS
- Encrypt data in transit
- Authenticate servers using digital certificates
- Prevent eavesdropping and man-in-the-middle attacks

HTTPS uses SSL/TLS to secure web traffic between clients and servers.

---

## OpenSSL (Hands-on Demonstration)

OpenSSL is a command-line tool used to perform cryptographic operations.

### Encryption Example
```bash
openssl enc -aes-256-cbc -in file.txt -out file.enc

### Decryption Example
```bash
openssl enc -aes-256-cbc -d -in file.enc -out file.txt
