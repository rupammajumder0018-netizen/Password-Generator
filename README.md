# 🔐 Password Generator

A simple and lightweight **Python Password Generator** that creates random passwords using a combination of lowercase letters, uppercase letters, numbers, and special characters.

This project was built to practice Python fundamentals, modules, strings, lists, randomness, and user input handling.

---

## ✨ Features

- 🔢 Custom password length
- 🔤 Lowercase letters (`a-z`)
- 🔠 Uppercase letters (`A-Z`)
- 🔢 Numbers (`0-9`)
- 🔣 Special characters and punctuation
- 🎲 Randomized password generation
- ⚡ Lightweight and fast
- 🖥️ Command-line interface

---

## 🛠️ Technologies Used

- **Python 3**
- `random` — for randomizing characters
- `string` — for accessing letters, digits, and punctuation

No external libraries are required.

---
📥 Installation
1. Clone the Repository
git clone https://github.com/rupammajumder0018-netizen/Password-Generator.git
2. Navigate to the Project
cd Password-Generator
3. Navigate to the Python File
cd "Password generator"
4. Run the Program
python password.py
💻 Usage

After running the program, enter the desired password length.

Example
Enter your password length:
12


Your password is:


a8@Kz!2Qp#Lm

The program generates a randomized password based on the requested length.

🔎 How It Works

The program uses Python's built-in string module to access different character sets:

string.ascii_lowercase
string.ascii_uppercase
string.digits
string.punctuation

These character sets are combined and randomized using Python's random module.

The program then selects the required number of characters and combines them to create the final password.

🔄 Program Flow
User enters password length
            ↓
Collect lowercase letters
            ↓
Collect uppercase letters
            ↓
Collect numbers
            ↓
Collect special characters
            ↓
Combine characters
            ↓
Randomize characters
            ↓
Select requested length
            ↓
Display generated password

## 📂 Project Structure

```text
Password-Generator/
│
├── Password generator/
│   └── password.py
│
└── README.md


