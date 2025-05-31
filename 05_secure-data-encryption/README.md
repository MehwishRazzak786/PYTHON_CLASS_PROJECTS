# 🔐 Secure Data Encryption System

This is a Streamlit-based web app that allows users to **securely store and retrieve encrypted data** using a passkey. Encryption is performed using the `cryptography` library (Fernet), and all data is stored temporarily in memory.

---

## 🚀 Features

- 🔐 **Encrypt & Store Data** using a passkey
- 🔓 **Decrypt & Retrieve Data** with correct authentication
- 🚫 **3 Attempt Limit** to prevent brute-force attacks
- 🔁 **Login Page** for admin re-authorization after failed attempts
- 🧠 **In-memory storage** (no database used)

---

## 🛠️ Technologies Used

- [Streamlit](https://streamlit.io/)
- [Cryptography (Fernet)](https://cryptography.io/)
- Python `hashlib` for passkey hashing

---

## 📦 Installation

#### 1. Clone the repository

```bash
git clone https://github.com/MehwishRazzak786/PYTHON_CLASS_PROJECTS
      cd 05_secure-data-encryption


2. Create and activate a virtual environment

# Create virtual environment
python -m venv env

# Activate (Windows)
env\Scripts\activate

# Activate (Mac/Linux)
source env/bin/activate


3. Install dependencies

pip install -r requirements.txt


▶️ Running the App

streamlit run main.py


🔐 Admin Login
In case of too many failed passkey attempts, the user is redirected to login page.

Username: admin
Password: admin123


📂 Project Structure

data-encryption/
├── env/                   # Virtual environment (ignored in Git)
├── main.py                # Main Streamlit application
├── .gitignore             # Git ignore file
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies


⚠️ Notes
- This app uses in-memory storage only. Restarting the app will clear all data.

- The env/ folder is excluded from GitHub via .gitignore.


📄 License
This project is for educational/demo use only. No data is permanently stored or shared.


