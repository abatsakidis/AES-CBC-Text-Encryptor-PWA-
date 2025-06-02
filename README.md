# 🔐 AES CBC Text Encryptor (PWA)

A lightweight **Progressive Web App (PWA)** built with HTML, JavaScript, and CryptoJS that allows you to **encrypt and decrypt text** using **AES encryption in CBC mode** with **SHA-256 password hashing**.

---

### ✨ Features

- 🔒 AES encryption/decryption (CBC mode, PKCS7 padding)
- 🔑 Password-based key derivation using SHA-256
- 🔁 Random IV generation for each encryption
- 💾 Save encrypted/decrypted results as `.txt` files
- 📁 Load text input from local files
- ⚙️ Offline functionality (PWA - installable web app)

> Perfect for local, client-side text protection — no server or internet connection required.

---

### 🔧 How to Use

#### 🔹 Open the App
Just open `index.html` in your browser, or deploy it online to benefit from full PWA functionality.

#### 🔹 Encrypt Text
- Type or paste your plain text into the top textarea.
- Enter your password in the password field.
- Click 🔒 **Encrypt**.
- The encrypted result will appear in the output field (Base64-encoded).

#### 🔹 Decrypt Text
- Paste the encrypted Base64 string into the top textarea.
- Enter the password used for encryption.
- Click 🔓 **Decrypt** to reveal the original text.

#### 🔹 Save to File
- After encryption or decryption, click 💾 **Save** to download the result as a `.txt` file.

#### 🔹 Load from File
- Click 📁 **Load File** to upload a text file. Its contents will be loaded into the input field.

#### 🔹 Install as PWA
- If accessed from a browser that supports PWAs, you can install it to your device for offline use.

> ⚠️ **Note:** Always remember your password. Encrypted data cannot be recovered without the correct key.

---

### 📸 Screenshot

![App Screenshot](screenshot/screen.jpg)

