# 🔐 Python Cipher Project

A simple Python project implementing classic encryption algorithms such as Caesar Cipher and Vigenère Cipher. Great for learning the basics of cryptography, string manipulation, and Python functions.

## 📦 Features

- ✅ Caesar Cipher (Encryption & Decryption)
- ✅ Vigenère Cipher (Encryption & Decryption)
- ✅ Command-line interface
- ✅ Clean and modular code
- ✅ Easy to extend with additional ciphers

## 🛠️ Technologies Used

- Python 3.x
- Standard Library only (no external dependencies)

## 🚀 Getting Started

### Prerequisites
Make sure you have Python 3 installed.

```bash
python3 --version
```

### Clone the Repo

```bash
git clone https://github.com/yourusername/python-cipher-project.git
cd python-cipher-project
```

### Run the Program

```bash
python3 main.py
```

You’ll be prompted to:
- Select a cipher
- Choose encrypt or decrypt
- Enter your message and key

## 🧠 Examples

### Caesar Cipher

```plaintext
Enter your message: HELLO
Enter shift (number): 3
Encrypted message: KHOOR
```

### Vigenère Cipher

```plaintext
Enter your message: HELLO
Enter keyword: KEY
Encrypted message: RIJVS
```

## 📁 Project Structure

```
python-cipher-project/
│
├── ciphers/
│   ├── caesar.py
│   ├── vigenere.py
│
├── main.py
├── utils.py
└── README.md
```

- `main.py`: Entry point and user interface
- `ciphers/`: Contains individual cipher modules
- `utils.py`: Helper functions for validation or formatting

## 📚 Learning Goals

- Understand the basics of encryption and decryption
- Practice Python string manipulation and modular design
- Get familiar with writing CLI tools

## ✨ Future Improvements

- Add support for additional ciphers (e.g., Atbash, Playfair)
- Build a simple GUI using Tkinter or PyQt
- Add file encryption support
- Unit testing

## 🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to add.

## 📄 License

MIT License

---

Made with 💻 + 🔐 by Johanna Schnell
```

---

Let me know if you'd like to include instructions for a specific cipher (like ROT13, Base64, etc.), or if you're planning to deploy it as a web app or package it!
