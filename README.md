# 🔐File_Integrity_Checker
A simple Python-based tool that ensures the integrity and security of files by calculating and comparing their cryptographic hash values (SHA-256).It helps detect unauthorized or accidental changes in files over time.

# ✅Features
Calculates SHA-256 hash values of files.
Tracks changes by comparing current hash with stored hash values.
Alerts if a file is modified, unchanged, or newly added.
Saves all hash data in a local stored_hashes.json file.
Supports multiple files at once.

# 📂Use Cases
Monitor sensitive or important files for unauthorized changes.
Check if downloaded files have been altered.
Build part of a security auditing or backup verification system.

# Getting Started

🔸 Run the Script
python file_integrity_checker.py

🔸 Input Example:
![image](https://github.com/user-attachments/assets/6e2eed24-d4ee-4002-8af1-3df613b0d617)

🟢 Output Example:
![image](https://github.com/user-attachments/assets/6c43ac13-794d-4108-b557-9852c7685c6e)

# 📁 Files Generated
stored_hashes.json – Stores the original hash values for comparison.

# 🛠 Built With

Python 3.x
hashlib – For cryptographic hash generation
json – For storing file hashes locally










