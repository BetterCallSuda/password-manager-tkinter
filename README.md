# password-manager-tkinter
A secure password manager built with Python and Tkinter that generates strong passwords, stores them in a JSON file, and allows searching saved credentials.


Project Structure
python-password-manager/
│
├── main.py
├── README.md
├── requirements.txt
├── data.json          # created automatically at runtime
├── logo.png
└── .gitignore

📘 README.md (Copy–Paste Ready)
# Python Password Manager 🔐

A desktop password manager built using **Python** and **Tkinter**.  
The application generates strong passwords, stores credentials securely in a JSON file, and allows users to search saved passwords easily.

---

## ✨ Features

- Strong password generator
- Copy password to clipboard automatically
- Save website credentials securely
- Search stored passwords
- JSON-based local storage
- Clean and simple GUI

---

## 🛠️ Tech Stack

- Python
- Tkinter (GUI)
- JSON (data storage)
- Pyperclip (clipboard support)

---

## 🚀 How to Run the Application

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/python-password-manager.git

2️⃣ Navigate into the project directory
cd python-password-manager

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the app
python main.py

🔐 How It Works

Enter the website name and email/username.

Generate a strong password or enter one manually.

Save the credentials securely in a JSON file.

Use the search feature to retrieve stored credentials.

Passwords can be copied directly to the clipboard.

📂 Data Storage

Passwords are stored locally in a file called data.json using the following format:

{
  "example.com": {
    "email": "user@example.com",
    "password": "strongpassword123"
  }
}

📚 What I Learned

Building GUI applications with Tkinter

Password generation logic

JSON file handling

Error handling using try/except

Clipboard automation

User input validation

🔮 Future Improvements

Encrypt stored passwords

Add master password authentication

Improve UI design

Export/import password data

Auto-lock after inactivity
