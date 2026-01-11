# 🔐 Cipher Simulation

A web-based simulation of classical cryptographic ciphers implemented using **HTML, CSS, and JavaScript**.

This project demonstrates the working principles of:
- Caesar Cipher
- Multiplicative Cipher

Designed as an educational tool for understanding basic encryption and decryption techniques.

---

## ✨ Features

- Encrypt and decrypt text using Caesar Cipher
- Encrypt and decrypt text using Multiplicative Cipher
- Clean and simple UI
- Input validation for cryptographic keys
- Modular inverse–based decryption for multiplicative cipher

---

## 🧮 Ciphers Implemented

### 1. Caesar Cipher
- **Encryption:**  
  \[
  E(x) = (x + k) \mod 26
  \]
- **Decryption:**  
  \[
  D(x) = (x - k) \mod 26
  \]

### 2. Multiplicative Cipher
- **Encryption:**  
  \[
  E(x) = (x \times k) \mod 26
  \]
- **Decryption:**  
  \[
  D(x) = (x \times k^{-1}) \mod 26
  \]
  *(where \( k^{-1} \) is the modular inverse of \( k \) modulo 26)*

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cipher-simulation.git
