# Free In-Browser Cryptography & Security Tools 🛡️

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](https://opensource.org/licenses/MIT)
[![Web Crypto API](https://img.shields.io/badge/W3C-Web_Crypto_API-06b6d4.svg)](https://www.w3.org/TR/WebCryptoAPI/)
[![Zero Telemetry](https://img.shields.io/badge/Privacy-Zero_Server_Uploads-10b981.svg)](https://webcryptotools.com/privacy)
[![Total Tools](https://img.shields.io/badge/Utilities-105_Live_Tools-blue.svg)](https://webcryptotools.com/tools)

> A curated, open-source collection of **105 client-side cryptographic utilities, hash generators, token decoders, and ciphers**. All tools run 100% locally in your browser thread via the W3C Web Cryptography API (`window.crypto.subtle`). Zero telemetry, zero server uploads.

🔗 **Live Platform:** [https://webcryptotools.com](https://webcryptotools.com)

---

## ⚡ Why In-Browser Cryptography Matters

Pasting production JWTs, private keys, or enterprise hashes into online converters poses severe security risks and violates SOC2/HIPAA data handling requirements. 

**WebCryptoTools** was architected to eliminate this hazard:
1. **Zero Remote Telemetry:** Open your browser's DevTools Network tab (`F12`) to confirm 0 network requests are made during cryptographic operations.
2. **Hardware Accelerated:** Leverages native browser CPU instructions for sub-millisecond execution.
3. **Offline Functional:** Disconnect your internet connection after loading; all 105 tools remain fully operational.

---

## 📂 Complete Tools Directory (105 Tools)

### Hashing & Checksums (20 Tools)

> Cryptographic hash functions and data integrity checksums running entirely in your browser. &middot; [Explore Suite](https://webcryptotools.com/category/hashing)

| Tool Name | Algorithm | Description | Link |
| :--- | :--- | :--- | :--- |
| **SHA-256 Hash Generator** | `SHA-256` | Calculate 256-bit SHA-256 cryptographic hashes instantly in your browser using the native Web Cryptography API. Zero data upload, 100% private. | [Launch Tool](https://webcryptotools.com/tools/sha256-hash-generator) |
| **SHA-512 Hash Generator** | `SHA-512` | Compute 512-bit SHA-512 cryptographic digests locally in your browser. Generates 128-character hexadecimal hashes with zero server transmission. | [Launch Tool](https://webcryptotools.com/tools/sha512-hash-generator) |
| **SHA-384 Hash Generator** | `SHA-384` | Generate 384-bit SHA-384 cryptographic digests in your browser. Standard for Suite B cryptographic algorithms and TLS 1.3. | [Launch Tool](https://webcryptotools.com/tools/sha384-hash-generator) |
| **SHA-224 Hash Generator** | `SHA-224` | Calculate 224-bit SHA-224 cryptographic digests. Useful for two-key Triple DES matching and legacy compliance. | [Launch Tool](https://webcryptotools.com/tools/sha224-hash-generator) |
| **SHA-1 Hash Generator** | `SHA-1` | Calculate 160-bit SHA-1 hashes client-side. Commonly used for Git commit hashing and checksum verification. | [Launch Tool](https://webcryptotools.com/tools/sha1-hash-generator) |
| **MD5 Hash Generator** | `MD5` | Generate 128-bit MD5 checksums instantly in your browser. Ideal for cache keys, file verification, and legacy checksums. | [Launch Tool](https://webcryptotools.com/tools/md5-hash-generator) |
| **MD4 Hash Generator** | `MD4` | Calculate MD4 cryptographic message digests. Used in Microsoft NTLM password hashes and legacy protocol research. | [Launch Tool](https://webcryptotools.com/tools/md4-hash-generator) |
| **Keccak-256 Hash Generator** | `Keccak-256` | Calculate Ethereum Keccak-256 hashes in your browser. Standard for Solidity function selectors, ERC-20 signatures, and smart contracts. | [Launch Tool](https://webcryptotools.com/tools/keccak256-hash-generator) |
| **Keccak-512 Hash Generator** | `Keccak-512` | Generate 512-bit Keccak-512 cryptographic digests. High-security pre-NIST Sponge function used in advanced cryptographic systems. | [Launch Tool](https://webcryptotools.com/tools/keccak512-hash-generator) |
| **SHA3-256 Hash Generator** | `SHA3-256` | Compute official NIST FIPS 202 SHA3-256 cryptographic hashes locally in your browser. Next-generation Keccak-based hashing. | [Launch Tool](https://webcryptotools.com/tools/sha3-256-hash-generator) |
| **SHA3-512 Hash Generator** | `SHA3-512` | Generate 512-bit SHA3-512 cryptographic digests. Maximum security standard of the NIST FIPS 202 sponge algorithm family. | [Launch Tool](https://webcryptotools.com/tools/sha3-512-hash-generator) |
| **SHA3-384 Hash Generator** | `SHA3-384` | Calculate 384-bit NIST SHA3-384 cryptographic digests with zero server logging. 96-hex character output. | [Launch Tool](https://webcryptotools.com/tools/sha3-384-hash-generator) |
| **SHA3-224 Hash Generator** | `SHA3-224` | Calculate 224-bit NIST SHA3-224 cryptographic digests locally in your browser. 56-hex character output. | [Launch Tool](https://webcryptotools.com/tools/sha3-224-hash-generator) |
| **RIPEMD-160 Hash Generator** | `RIPEMD-160` | Calculate 160-bit RIPEMD-160 cryptographic hashes. Used in Bitcoin address generation (HASH160: SHA256 + RIPEMD160). | [Launch Tool](https://webcryptotools.com/tools/ripemd160-hash-generator) |
| **CRC-32 Checksum Calculator** | `CRC-32` | Calculate 32-bit cyclic redundancy check (CRC-32) checksums. Standard for ZIP archives, PNG chunks, and Ethernet frames. | [Launch Tool](https://webcryptotools.com/tools/crc32-checksum-calculator) |
| **CRC-16 Checksum Calculator** | `CRC-16` | Calculate 16-bit CRC-16 checksums (Modbus, CCITT, XMODEM standards) in your browser for embedded systems and serial protocols. | [Launch Tool](https://webcryptotools.com/tools/crc16-checksum-calculator) |
| **BLAKE2b Hash Generator** | `BLAKE2b` | Compute 512-bit BLAKE2b cryptographic hashes. Faster than MD5, SHA-1, and SHA-256 while providing equal or greater security. | [Launch Tool](https://webcryptotools.com/tools/blake2b-hash-generator) |
| **BLAKE2s Hash Generator** | `BLAKE2s` | Compute 256-bit BLAKE2s cryptographic hashes optimized for 8 to 32-bit platforms, embedded devices, and WireGuard protocols. | [Launch Tool](https://webcryptotools.com/tools/blake2s-hash-generator) |
| **BLAKE3 Hash Generator** | `BLAKE3` | Calculate next-generation BLAKE3 cryptographic hashes. Highly parallel tree-hashing algorithm providing maximum performance and security. | [Launch Tool](https://webcryptotools.com/tools/blake3-hash-generator) |
| **Whirlpool Hash Generator** | `Whirlpool` | Generate 512-bit Whirlpool cryptographic digests based on a modified Advanced Encryption Standard (AES) cipher block structure. | [Launch Tool](https://webcryptotools.com/tools/whirlpool-hash-generator) |

### Passwords & Key Derivation (12 Tools)

> Bcrypt, PBKDF2, HMAC, Scrypt, password entropy analyzers and secure passphrase generators. &middot; [Explore Suite](https://webcryptotools.com/category/passwords)

| Tool Name | Algorithm | Description | Link |
| :--- | :--- | :--- | :--- |
| **Bcrypt Hash Generator** | `Bcrypt` | Generate secure Blowfish-based Bcrypt password hashes ($2a$, $2b$, $2y$) with configurable salt work factor rounds (4 to 14) in your browser. | [Launch Tool](https://webcryptotools.com/tools/bcrypt-hash-generator) |
| **Bcrypt Hash Verifier** | `Bcrypt Verify` | Verify if a plaintext password matches an existing Bcrypt hash string ($2a$, $2b$, $2y$). 100% client-side verification. | [Launch Tool](https://webcryptotools.com/tools/bcrypt-hash-verifier) |
| **PBKDF2 Key Derivation Generator** | `PBKDF2` | Derive cryptographic keys using Password-Based Key Derivation Function 2 (PBKDF2) with SHA-256, configurable iterations and salt in your browser. | [Launch Tool](https://webcryptotools.com/tools/pbkdf2-key-derivation) |
| **HMAC-SHA256 Generator** | `HMAC-SHA256` | Generate Hash-based Message Authentication Codes (HMAC-SHA256) with a secret key. Standard for AWS, Stripe, GitHub and Twilio webhook signatures. | [Launch Tool](https://webcryptotools.com/tools/hmac-sha256-generator) |
| **HMAC-SHA512 Generator** | `HMAC-SHA512` | Compute 512-bit HMAC-SHA512 message authentication codes using shared secret keys in your browser. | [Launch Tool](https://webcryptotools.com/tools/hmac-sha512-generator) |
| **HMAC-MD5 Generator** | `HMAC-MD5` | Calculate HMAC-MD5 keyed-hash message authentication codes for legacy API compatibility and network protocol verification. | [Launch Tool](https://webcryptotools.com/tools/hmac-md5-generator) |
| **HMAC-SHA1 Generator** | `HMAC-SHA1` | Compute HMAC-SHA1 signatures. Standard signature method for OAuth 1.0a, TOTP (Google Authenticator) and legacy systems. | [Launch Tool](https://webcryptotools.com/tools/hmac-sha1-generator) |
| **Password Entropy & Strength Analyzer** | `NIST Entropy` | Calculate mathematical Shannon entropy in bits, crack-time estimations, character space analysis, and NIST SP 800-63B compliance locally in your browser. | [Launch Tool](https://webcryptotools.com/tools/password-entropy-analyzer) |
| **Diceware Passphrase Generator** | `Diceware / WebCrypto` | Generate memorable, high-entropy multi-word passphrases using the official EFF wordlist and cryptographically secure random integers (crypto.getRandomValues). | [Launch Tool](https://webcryptotools.com/tools/diceware-passphrase-generator) |
| **Cryptographically Secure Password Generator** | `Web Crypto CSPRNG` | Generate high-entropy random passwords using window.crypto.getRandomValues. Configure length, symbols, numbers, and avoid ambiguous characters. | [Launch Tool](https://webcryptotools.com/tools/secure-password-generator) |
| **Scrypt Hash Generator** | `Scrypt` | Compute memory-hard Scrypt key derivations and password hashes. Designed to resist hardware ASIC and GPU brute-force cracking. | [Launch Tool](https://webcryptotools.com/tools/scrypt-hash-generator) |
| **Argon2 Hash Generator** | `Argon2id` | Calculate Argon2id, Argon2i, and Argon2d hashes. Winner of the Password Hashing Competition (PHC) and modern gold-standard for password storage. | [Launch Tool](https://webcryptotools.com/tools/argon2-hash-generator) |

### JWT & API Tokens (12 Tools)

> Decode, sign, verify and inspect JSON Web Tokens (JWT), PASETO, API keys and CSRF tokens. &middot; [Explore Suite](https://webcryptotools.com/category/tokens)

| Tool Name | Algorithm | Description | Link |
| :--- | :--- | :--- | :--- |
| **JWT Token Decoder** | `RFC 7519` | Decode and inspect JSON Web Tokens (JWT) client-side. Parse header, payload claims (iss, sub, exp, iat), and signature without sending tokens to any server. | [Launch Tool](https://webcryptotools.com/tools/jwt-decoder) |
| **JWT Signature Verifier** | `HMAC / RSA` | Verify HMAC (HS256, HS384, HS512) or RSA/ECDSA signatures of JWT tokens client-side using Web Crypto API. Confirm payload integrity locally. | [Launch Tool](https://webcryptotools.com/tools/jwt-signature-verifier) |
| **JWT Token Builder & Signer** | `RFC 7519 Sign` | Build and sign custom JSON Web Tokens (JWT) in your browser. Configure claims, expiration (exp), audience (aud), and sign with HS256 or RS256. | [Launch Tool](https://webcryptotools.com/tools/jwt-builder-signer) |
| **JWT Expiration & Claims Inspector** | `RFC 7519 Claims` | Inspect JWT expiration (exp), issued-at (iat), and not-before (nbf) timestamps with human-readable local time, countdown timers, and validity checks. | [Launch Tool](https://webcryptotools.com/tools/jwt-expiry-inspector) |
| **JWK to PEM Converter** | `JWK/PEM` | Convert JSON Web Keys (JWK) into standard PKCS#8 or SPKI PEM formatted public and private keys in your browser. | [Launch Tool](https://webcryptotools.com/tools/jwk-to-pem-converter) |
| **PEM to JWK Converter** | `PEM/JWK` | Convert standard PEM public or private keys into JSON Web Key (JWK) format for OAuth 2.0 and OpenID Connect JWKS endpoints. | [Launch Tool](https://webcryptotools.com/tools/pem-to-jwk-converter) |
| **PASETO Token Decoder** | `PASETO` | Decode and inspect PASETO (Platform-Agnostic Security Tokens) v1, v2, v3, and v4 local and public tokens without leaking claims. | [Launch Tool](https://webcryptotools.com/tools/paseto-token-decoder) |
| **Secure API Key Generator (with Custom Prefix)** | `CSPRNG Base62` | Generate high-entropy API keys with custom prefixes (e.g., sk_live_..., pk_test_..., ghp_...) and CRC32 checksum verification tails in your browser. | [Launch Tool](https://webcryptotools.com/tools/api-key-generator) |
| **CSRF Token Generator** | `CSPRNG Hex/Base64` | Generate cryptographically random Cross-Site Request Forgery (CSRF / XSRF) anti-tamper tokens in Hex and Base64 format locally. | [Launch Tool](https://webcryptotools.com/tools/csrf-token-generator) |
| **Bearer Token Generator** | `OAuth 2.0 Bearer` | Generate OAuth 2.0 Bearer authentication tokens with high cryptographic randomness for testing API authorization headers. | [Launch Tool](https://webcryptotools.com/tools/bearer-token-generator) |
| **Fernet Token Decoder** | `Fernet AES-CBC` | Decode and inspect Python cryptography Fernet symmetric tokens. Parse timestamp, initialization vector (IV), ciphertext, and HMAC. | [Launch Tool](https://webcryptotools.com/tools/fernet-token-decoder) |
| **JWT to JSON Payload Converter** | `JSON Parser` | Extract and format the payload of any JWT into formatted, beautified JSON with one click. Clean, minimal, and fast. | [Launch Tool](https://webcryptotools.com/tools/jwt-to-json) |

### Ciphers & Encryption (12 Tools)

> Symmetric encryption using AES-GCM, AES-CBC, ChaCha20-Poly1305, 3DES and classical ciphers. &middot; [Explore Suite](https://webcryptotools.com/category/encryption)

| Tool Name | Algorithm | Description | Link |
| :--- | :--- | :--- | :--- |
| **AES-256-GCM Encryptor & Decryptor** | `AES-GCM` | Authenticated encryption and decryption using AES-256-GCM (Galois/Counter Mode) via the native Web Cryptography API. Total data privacy. | [Launch Tool](https://webcryptotools.com/tools/aes-256-gcm-encrypt) |
| **AES-128-GCM Encryptor & Decryptor** | `AES-GCM` | Encrypt and decrypt data using 128-bit AES-GCM via browser WebCrypto. Fast, authenticated symmetric encryption. | [Launch Tool](https://webcryptotools.com/tools/aes-128-gcm-encrypt) |
| **AES-256-CBC Encryptor & Decryptor** | `AES-CBC` | Encrypt and decrypt using AES-256-CBC (Cipher Block Chaining) with PKCS#7 padding and random initialization vectors in your browser. | [Launch Tool](https://webcryptotools.com/tools/aes-256-cbc-encrypt) |
| **AES-128-CBC Encryptor & Decryptor** | `AES-CBC` | Encrypt and decrypt using 128-bit AES in CBC mode with PKCS#7 padding client-side. | [Launch Tool](https://webcryptotools.com/tools/aes-128-cbc-encrypt) |
| **AES-CTR Stream Encryptor & Decryptor** | `AES-CTR` | Encrypt and decrypt data using AES in Counter (CTR) mode. Converts block ciphers into stream ciphers with zero padding required. | [Launch Tool](https://webcryptotools.com/tools/aes-ctr-encrypt) |
| **ChaCha20-Poly1305 Encryptor** | `ChaCha20-Poly1305` | Encrypt data using ChaCha20-Poly1305 AEAD stream cipher. High-speed cipher used in WireGuard, TLS 1.3 and Android devices. | [Launch Tool](https://webcryptotools.com/tools/chacha20-poly1305-encrypt) |
| **Triple DES (3DES) Encryptor** | `Triple DES` | Encrypt and decrypt using Triple DES (EDE3 / 3DES) for legacy financial systems and banking smart card compliance. | [Launch Tool](https://webcryptotools.com/tools/triple-des-3des-encrypt) |
| **DES Encryptor & Decryptor** | `DES` | Encrypt and decrypt data using the historic 56-bit Data Encryption Standard (DES). For cryptographic education and legacy research. | [Launch Tool](https://webcryptotools.com/tools/des-encrypt) |
| **Blowfish Encryptor & Decryptor** | `Blowfish` | Encrypt and decrypt text using Bruce Schneier's classic Blowfish symmetric block cipher with variable key lengths up to 448 bits. | [Launch Tool](https://webcryptotools.com/tools/blowfish-encrypt) |
| **RC4 Stream Cipher Encryptor** | `RC4 (ARCFOUR)` | Encrypt and decrypt data using the classic Rivest Cipher 4 (RC4 / ARCFOUR) stream cipher for security research and WEP/SSL analysis. | [Launch Tool](https://webcryptotools.com/tools/rc4-encrypt) |
| **XOR String Cipher Encryptor** | `XOR` | Perform symmetric bitwise XOR encryption and decryption on strings with repeating multi-character keys. | [Launch Tool](https://webcryptotools.com/tools/xor-string-cipher) |
| **ROT13 & Caesar Cipher Tool** | `ROT13 / Caesar` | Encrypt and decrypt text with ROT13, ROT47, and classical Caesar substitution ciphers with custom alphabet shift values. | [Launch Tool](https://webcryptotools.com/tools/rot13-caesar-cipher) |

### Public Keys & Signatures (12 Tools)

> Generate RSA, Ed25519, Curve25519, ECDSA, SSH keys and sign or verify digital signatures. &middot; [Explore Suite](https://webcryptotools.com/category/keys)

| Tool Name | Algorithm | Description | Link |
| :--- | :--- | :--- | :--- |
| **RSA Key Pair Generator (2048 & 4096-bit)** | `RSA-OAEP / PSS` | Generate cryptographically secure 2048-bit, 3072-bit, and 4096-bit RSA public and private key pairs in standard PKCS#8 and SPKI PEM format in your browser. | [Launch Tool](https://webcryptotools.com/tools/rsa-key-pair-generator) |
| **Ed25519 Key Pair Generator** | `Ed25519` | Generate high-speed, collision-resistant Ed25519 Edwards-curve Digital Signature Algorithm key pairs in OpenSSH and PEM formats. | [Launch Tool](https://webcryptotools.com/tools/ed25519-key-pair-generator) |
| **Curve25519 Key Pair Generator** | `X25519 ECDH` | Generate Curve25519 (X25519) key pairs for Diffie-Hellman key exchange. Used in Signal Protocol, WireGuard, and WhatsApp encryption. | [Launch Tool](https://webcryptotools.com/tools/curve25519-key-generator) |
| **ECDSA P-256 Key Pair Generator** | `ECDSA P-256` | Generate NIST P-256 (secp256r1 / prime256v1) elliptic curve public and private key pairs via browser WebCrypto for TLS and WebAuthn/Passkeys. | [Launch Tool](https://webcryptotools.com/tools/ecdsa-p256-key-generator) |
| **ECDSA P-384 Key Pair Generator** | `ECDSA P-384` | Generate high-security NIST P-384 (secp384r1) elliptic curve key pairs for Suite B commercial national security systems. | [Launch Tool](https://webcryptotools.com/tools/ecdsa-p384-key-generator) |
| **secp256k1 (Bitcoin/Ethereum) Key Pair Generator** | `secp256k1` | Generate Koblitz curve secp256k1 key pairs used by Bitcoin, Ethereum, and EVM blockchains. View private key, public key, and derived uncompressed hex. | [Launch Tool](https://webcryptotools.com/tools/secp256k1-key-generator) |
| **SSH Key Pair Generator (OpenSSH / ed25519 / RSA)** | `OpenSSH` | Generate SSH keys (ed25519 and RSA 4096) directly in OpenSSH format (id_ed25519 and id_ed25519.pub) for GitHub, GitLab, and Linux servers. | [Launch Tool](https://webcryptotools.com/tools/ssh-keygen-online) |
| **RSA Public Key Encryptor** | `RSA-OAEP` | Encrypt secret payloads using an RSA public key (RSA-OAEP with SHA-256) in your browser. Only the private key holder can decrypt. | [Launch Tool](https://webcryptotools.com/tools/rsa-public-key-encrypt) |
| **RSA Private Key Decryptor** | `RSA-OAEP` | Decrypt RSA-OAEP encrypted payloads using your private key locally in your browser. Safe execution with zero network telemetry. | [Launch Tool](https://webcryptotools.com/tools/rsa-private-key-decrypt) |
| **Digital Signature Signer (RSA/ECDSA)** | `Digital Signature` | Sign messages, hashes, and contracts using an RSA or ECDSA private key with SHA-256. Generate verifiable digital signatures in your browser. | [Launch Tool](https://webcryptotools.com/tools/digital-signature-signer) |
| **Digital Signature Verifier** | `Signature Verify` | Verify digital signatures against a plaintext message using an RSA or ECDSA public key in your browser. Confirm data integrity. | [Launch Tool](https://webcryptotools.com/tools/digital-signature-verifier) |
| **PGP / GPG Public Key Inspector** | `OpenPGP RFC 4880` | Inspect OpenPGP (GPG) public key blocks (-----BEGIN PGP PUBLIC KEY BLOCK-----). Parse Key ID, User ID, creation date, subkeys, and algorithm client-side. | [Launch Tool](https://webcryptotools.com/tools/pgp-key-inspector) |

### SSL/TLS & Certificates (10 Tools)

> Parse X.509 PEM certificates, CSRs, inspect SSL expiry, SAN domains and extract PKCS#12 bundles. &middot; [Explore Suite](https://webcryptotools.com/category/certificates)

| Tool Name | Algorithm | Description | Link |
| :--- | :--- | :--- | :--- |
| **X.509 Certificate (PEM/CRT) Decoder** | `X.509 ASN.1` | Decode and inspect X.509 SSL/TLS certificates (PEM/CRT format) client-side. View Subject, Issuer, Validity Period, SANs, and Serial Number with zero data leaks. | [Launch Tool](https://webcryptotools.com/tools/x509-certificate-decoder) |
| **SSL Certificate Expiry & Validity Checker** | `X.509 Dates` | Check the exact validity period, notBefore, notAfter, and countdown days remaining before your SSL/TLS certificate expires. | [Launch Tool](https://webcryptotools.com/tools/ssl-certificate-expiry-checker) |
| **CSR (Certificate Signing Request) Decoder** | `PKCS#10` | Decode Certificate Signing Requests (CSR) in PEM format (-----BEGIN CERTIFICATE REQUEST-----). Verify Common Name (CN), Organization, and SANs before submitting to a CA. | [Launch Tool](https://webcryptotools.com/tools/csr-decoder) |
| **Self-Signed SSL Certificate Generator** | `X.509 Generator` | Generate self-signed SSL/TLS certificates and private keys locally in your browser for local development (localhost), Docker, and staging environments. | [Launch Tool](https://webcryptotools.com/tools/self-signed-certificate-generator) |
| **PEM to DER Converter** | `ASN.1 Binary` | Convert ASCII Base64 PEM certificates and keys into raw binary DER (Distinguished Encoding Rules) format in your browser. | [Launch Tool](https://webcryptotools.com/tools/pem-to-der-converter) |
| **DER to PEM Converter** | `Base64 ASN.1` | Convert binary DER certificates and keys into standard Base64 PEM format with appropriate header tags in your browser. | [Launch Tool](https://webcryptotools.com/tools/der-to-pem-converter) |
| **PFX / PKCS#12 Certificate Inspector** | `PKCS#12` | Inspect PFX / PKCS#12 bundle archives locally in your browser. Inspect certificate chains, friendly names, and bag attributes without uploading files. | [Launch Tool](https://webcryptotools.com/tools/pfx-pkcs12-inspector) |
| **CRL (Certificate Revocation List) Parser** | `RFC 5280 CRL` | Parse Certificate Revocation Lists (CRL). Inspect revoked certificate serial numbers, revocation dates, and next-update timestamps client-side. | [Launch Tool](https://webcryptotools.com/tools/crl-revocation-parser) |
| **TLS Cipher Suite Explainer & Lookup** | `IANA TLS` | Look up and dissect TLS 1.2 and TLS 1.3 cipher suites (e.g., TLS_AES_256_GCM_SHA384, ECDHE-RSA-AES128-GCM-SHA256). Learn key exchange, authentication, encryption, and MAC algorithms. | [Launch Tool](https://webcryptotools.com/tools/tls-cipher-suite-lookup) |
| **SAN (Subject Alternative Name) SSL Inspector** | `X.509 SAN` | Extract and inspect Subject Alternative Names (SAN) from SSL/TLS certificates. View all authorized domains, subdomains, and wildcard entries. | [Launch Tool](https://webcryptotools.com/tools/san-certificate-inspector) |

### Encodings & Converters (15 Tools)

> Fast binary-to-text converters: Base64, Base64URL, Base58 (Bitcoin), Base32, Hex, and URL encoding. &middot; [Explore Suite](https://webcryptotools.com/category/encoding)

| Tool Name | Algorithm | Description | Link |
| :--- | :--- | :--- | :--- |
| **Base64 Encoder & Decoder** | `RFC 4648 Base64` | Encode plaintext into Base64 or decode Base64 into UTF-8 strings and binary byte arrays in your browser. Fast, bidirectional, and private. | [Launch Tool](https://webcryptotools.com/tools/base64-encode-decode) |
| **Base64URL Safe Encoder & Decoder** | `RFC 4648 Base64URL` | Convert between standard Base64 and URL-safe Base64URL (- instead of +, _ instead of /, no = padding). Standard for JWT tokens and web URLs. | [Launch Tool](https://webcryptotools.com/tools/base64url-encode-decode) |
| **Base58 (Bitcoin/Solana) Encoder & Decoder** | `Base58` | Encode and decode Base58 strings used across Bitcoin, Solana, and IPFS. Excludes confusing characters (0, O, I, l) to prevent human reading errors. | [Launch Tool](https://webcryptotools.com/tools/base58-encode-decode) |
| **Base32 Encoder & Decoder** | `RFC 4648 Base32` | Encode and decode Base32 strings. Standard for TOTP two-factor authentication secret keys (Google Authenticator) and Tor onion addresses. | [Launch Tool](https://webcryptotools.com/tools/base32-encode-decode) |
| **Base85 / Ascii85 Encoder & Decoder** | `Ascii85` | Encode and decode Base85 (Ascii85) binary-to-text strings. Used in Adobe PDF files, Git binary patches, and btoa IPv6 representations. | [Launch Tool](https://webcryptotools.com/tools/base85-ascii85-encoder) |
| **Hex to String (ASCII/UTF-8) Converter** | `Hex Decoder` | Convert raw hexadecimal byte sequences (0x48656c6c6f) into human-readable ASCII and UTF-8 strings client-side. | [Launch Tool](https://webcryptotools.com/tools/hex-to-string) |
| **String to Hex Converter** | `Hex Encoder` | Convert plain text and Unicode strings into continuous or space-separated hexadecimal byte sequences. | [Launch Tool](https://webcryptotools.com/tools/string-to-hex) |
| **Hex to Binary Converter** | `Hex/Binary` | Convert hexadecimal strings into 8-bit padded binary strings (0s and 1s) with byte grouping in your browser. | [Launch Tool](https://webcryptotools.com/tools/hex-to-binary) |
| **Binary to Hex Converter** | `Binary/Hex` | Convert binary sequences (0s and 1s) into clean, compact hexadecimal strings client-side. | [Launch Tool](https://webcryptotools.com/tools/binary-to-hex) |
| **Binary to Text (ASCII) Converter** | `Binary Decoder` | Convert 8-bit binary code (01001000 01101001...) into readable ASCII and UTF-8 characters in your browser. | [Launch Tool](https://webcryptotools.com/tools/binary-to-text) |
| **Text to Binary Converter** | `Binary Encoder` | Convert plain text and symbols into 8-bit binary bytes (0s and 1s) with space separation in your browser. | [Launch Tool](https://webcryptotools.com/tools/text-to-binary) |
| **URL Component Encoder & Decoder** | `Percent-Encoding` | Percent-encode special characters in URLs (encodeURIComponent) or decode percent-encoded URLs into clean strings client-side. | [Launch Tool](https://webcryptotools.com/tools/url-encode-decode) |
| **HTML Entity Encoder & Decoder** | `HTML Entities` | Convert special HTML characters (&, <, >, ", ') into safe HTML entities (&amp;, &lt;, &gt;) to prevent Cross-Site Scripting (XSS). | [Launch Tool](https://webcryptotools.com/tools/html-entity-encode-decode) |
| **Punycode (IDN) International Domain Converter** | `Punycode IDNA` | Convert Internationalized Domain Names (IDN) with Unicode characters to ASCII Punycode (xn--...) and vice versa client-side. | [Launch Tool](https://webcryptotools.com/tools/punycode-idn-converter) |
| **Octal to Text & Text to Octal Converter** | `Base-8 Octal` | Convert base-8 octal byte sequences into readable text characters and convert plain text into octal notation in your browser. | [Launch Tool](https://webcryptotools.com/tools/octal-to-text-converter) |

### Unique IDs & Web3 (12 Tools)

> Generate RFC 9562 UUID v7, v4, ULID, NanoID, BIP-39 mnemonic seeds and validate crypto wallet addresses. &middot; [Explore Suite](https://webcryptotools.com/category/identifiers)

| Tool Name | Algorithm | Description | Link |
| :--- | :--- | :--- | :--- |
| **UUID v4 (Random) Generator** | `RFC 4122 v4` | Generate cryptographically random UUID v4 (Universally Unique Identifiers) in your browser using window.crypto.getRandomValues. Bulk generation available. | [Launch Tool](https://webcryptotools.com/tools/uuid-v4-generator) |
| **UUID v7 (Time-Ordered Modern RFC 9562) Generator** | `RFC 9562 v7` | Generate time-ordered UUID v7 identifiers specified in RFC 9562. Combines millisecond Unix timestamp with random bits for optimal database B-Tree index performance. | [Launch Tool](https://webcryptotools.com/tools/uuid-v7-generator) |
| **UUID v1 (Timestamp-Based) Generator** | `RFC 4122 v1` | Generate timestamp and MAC/node-based UUID v1 identifiers client-side. Inspect timestamp and sequence components. | [Launch Tool](https://webcryptotools.com/tools/uuid-v1-generator) |
| **UUID v5 (Namespace SHA-1) Generator** | `RFC 4122 v5` | Generate deterministic name-based UUID v5 identifiers using SHA-1 hashing of a namespace (DNS, URL, OID) and name string in your browser. | [Launch Tool](https://webcryptotools.com/tools/uuid-v5-generator) |
| **ULID (Universally Unique Lexicographically Sortable ID) Generator** | `ULID Spec` | Generate 26-character Crockford Base32 ULID identifiers. 128-bit compatibility with UUIDs, 1-millisecond timestamp precision, and URL-safe characters. | [Launch Tool](https://webcryptotools.com/tools/ulid-generator) |
| **ULID Timestamp & Randomness Decoder** | `ULID Parser` | Decode 26-character ULID strings into their exact Unix millisecond timestamp, human-readable ISO date, and 80-bit randomness payload in your browser. | [Launch Tool](https://webcryptotools.com/tools/ulid-decoder) |
| **NanoID Secure Collision-Resistant ID Generator** | `NanoID CSPRNG` | Generate compact, URL-friendly unique IDs using the NanoID algorithm. Smaller than UUID (21 characters) with equal or higher collision resistance. | [Launch Tool](https://webcryptotools.com/tools/nanoid-generator) |
| **CUID2 Secure Next-Gen Unique ID Generator** | `CUID2` | Generate collision-resistant, horizontal-scale CUID2 identifiers designed for modern web applications and distributed databases. | [Launch Tool](https://webcryptotools.com/tools/cuid2-generator) |
| **KSUID (K-Sortable Unique ID) Generator** | `Segment KSUID` | Generate Segment K-Sortable Unique Identifiers (KSUID). 27-character base62 strings sorted naturally by second-level timestamp. | [Launch Tool](https://webcryptotools.com/tools/ksuid-generator) |
| **Discord/Twitter Snowflake ID Timestamp Extractor** | `64-bit Snowflake` | Extract exact creation timestamps, worker IDs, and sequence numbers from 64-bit Snowflake IDs used by Discord, Twitter (X), and Mastodon in your browser. | [Launch Tool](https://webcryptotools.com/tools/snowflake-id-inspector) |
| **BIP-39 Mnemonic Seed Phrase Generator (12/24 Words)** | `BIP-39 CSPRNG` | Generate 12-word (128-bit) and 24-word (256-bit) BIP-39 mnemonic seed phrases using browser CSPRNG. Safe offline simulation with zero secrets logged. | [Launch Tool](https://webcryptotools.com/tools/bip39-mnemonic-generator) |
| **Crypto Address Validator (BTC, ETH, SOL)** | `Base58 / EIP-55` | Validate public blockchain addresses for Bitcoin (Legacy, SegWit, Taproot), Ethereum (EIP-55 checksum validation), and Solana in your browser. | [Launch Tool](https://webcryptotools.com/tools/crypto-address-validator) |

---

## 📚 Technical Cryptographic Guides

In-depth technical guides authored by the WebCryptoTools maintainer team:
* [UUID v7 vs UUID v4: Why Modern Databases Are Abandoning Random UUIDs](https://webcryptotools.com/guides/uuid-v7-vs-uuid-v4-database-performance)
* [The Definitive Guide to JWT Security: Avoiding Algorithm Confusion & Secret Leaks](https://webcryptotools.com/guides/jwt-security-best-practices-2026)
* [Password Hashing in 2026: Bcrypt vs Argon2id vs PBKDF2](https://webcryptotools.com/guides/bcrypt-vs-argon2id-vs-pbkdf2-password-hashing)
* [AES-GCM vs AES-CBC: Why Authenticated Encryption (AEAD) is Non-Negotiable](https://webcryptotools.com/guides/aes-gcm-vs-aes-cbc-authenticated-encryption)
* [Ed25519 vs RSA 4096: The Modern Asymmetric Cryptography Showdown](https://webcryptotools.com/guides/ed25519-vs-rsa-asymmetric-cryptography)

---

## 🤝 Contributing & Security Disclosures

Suggestions for new cryptographic primitives, algorithms, or bug reports are welcome via GitHub Issues. Responsible security disclosures can be emailed directly to `security@webcryptotools.com`.

## 📄 License
This curated repository is licensed under the [MIT License](LICENSE).
