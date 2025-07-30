Name:Pradhiba S
Company:CODTECH IT SOLUTIONS
ID:CT04DH1273
Domain:Cyber Security & Ethical Hacking
Duration:JULY 2 TO AUGUST 2

📄 Project Title:
File Integrity Checker

Objective:
To develop a Python-based tool that ensures the integrity of files by monitoring changes using secure hashing techniques (SHA-256). The goal is to detect any unauthorized or accidental modifications made to files.

Project Description:
The File Integrity Checker is a cybersecurity tool that calculates and stores the hash (a unique digital fingerprint) of a file when it's first added for monitoring. At any later time, it can re-calculate the hash and compare it with the original hash to check if the file has been altered.

If the hashes match, the file is confirmed to be unchanged and safe. If the hashes differ, it means the file has been modified, potentially indicating a data breach or unauthorized tampering.

Tools and Technologies Used:
Python,hashlib,Google Colab

Hashing Algorithm: SHA-256 (Advanced and secure)

Working Principle:
Hash Calculation:
The tool uses the SHA-256 algorithm to calculate the hash of the uploaded file.
This hash is saved as the file's original fingerprint.

Monitoring:
The tool re-checks the file by recalculating its hash whenever requested.
The new hash is compared with the stored original hash.

Result Evaluation:
If both hashes match → ✅ File is unchanged.
If hashes do not match → ⚠️ File has been modified.

OUTPUT:



Conclusion:
This project successfully demonstrates how file integrity can be protected using hash values. It is a useful and practical tool for detecting unauthorized file changes and is a great entry-level application in the field of cybersecurity and penetration testing.

