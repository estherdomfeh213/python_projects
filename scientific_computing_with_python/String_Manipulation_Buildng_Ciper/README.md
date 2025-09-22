# 🔐 Vigenère Cipher (Python)

This project implements a **Vigenère Cipher** in Python — a method of encrypting alphabetic text by using a series of interwoven Caesar ciphers based on the letters of a keyword.  

---

## 📜 Features
- Encrypt any text using a custom key  
- Decrypt encrypted text back to the original message  
- Handles non-alphabetic characters (keeps them unchanged)  
- Simple and lightweight implementation in pure Python  

---

## 🛠 How It Works
The script uses a **custom key** to shift letters of the message:  
- Each letter of the key determines the shift amount.  
- The key is repeated across the message.  
- Non-alphabet characters (spaces, punctuation) remain unchanged.  

---

## 🚀 Usage

### 1. Clone this repository
```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
````

### 2. Run the script

```bash
python vigenere.py
```

### 3. Example Output

```
Encrypted text: mrttaqrhknsw ih puggrur
Key: happycoding

Decrypted text: python is secure
```

---

## 📂 Project Structure

```
.
├── vigenere.py   # Main implementation of the cipher
└── README.md     # Project documentation
```

---

## ✨ Future Improvements

* Add a command-line interface for user input
* Support uppercase preservation
* Option to encrypt/decrypt files

---

## 👩‍💻 Author

Developed by **[Esther Domfeh](https://github.com/<estherdomfeh213>)**

