# Bank Management System (OOPs)

A secure, lightweight, and efficient **Bank Management System** built in Python leveraging core **Object-Oriented Programming (OOP)** principles. The application handles user registration, secure account matching, and financial ledger modifications, persisting all records cleanly in a local JSON dataset.

## 🚀 Features

* **Dynamic Account Creation:** Automatically provisions unique 7-character alphanumeric account numbers featuring custom symbol and type shuffling.
* **Encapsulated Account Verification:** Rejects user profiles during registration if eligibility constraints are missed (e.g., age under 18 or PIN lengths variations away from 4 digits).
* **Transactional Ledger Processing:** Robust routines to safely execute deposits and withdrawals alongside data boundary checks (e.g., maximum limits per single track deposit).
* **CRUD User Management:** Supports on-the-fly user profile detail modifications (Name, Email, PIN) and account purges via isolated class methods.
* **Crash-Resistant Persistence Layer:** Custom file-handling logic that safely catches structural JSON tracking noise and automatically initializes database configurations if the underlying storage file is empty or missing.

---

## 🛠️ Tech Stack & Architecture

* **Language:** Python 3.13+
* **Storage Framework:** Native JSON Serialization (`data.json`)
* **Design Paradigm:** Object-Oriented Programming (OOP) utilizing Class Methods, Encapsulation, and State Mutation.

---

## 📂 File Architecture

```text
Bank Management System OOPS/
├── app.py              # Main application configuration layer
├── main.py             # User Interface execution menus and testing runtime
├── modifie_code.py     # Core Bank class component holding backend logic
└── data.json           # Secure data serialization matrix
