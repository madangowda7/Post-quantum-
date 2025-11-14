A comprehensive cryptographic web application built to evaluate and compare the performance, size, and security levels of classical (RSA), post-quantum (Kyber, Dilithium), and hybrid cryptographic algorithms. Developed using Python (Flask backend) and React.js frontend, this project adheres to NIST recommendations and is tailored for benchmarking in constrained environments including mobile processors and IoT devices.

📌 Features
🛡️ Encryption Algorithms:

RSA (Classical)
Kyber (ML-KEM – Post-Quantum)
RSA + Kyber (Hybrid)
✍️ Digital Signature Algorithms:

RSA
Dilithium (ML-DSA – Post-Quantum)
RSA + Dilithium (Hybrid)
📊 Automatic Performance Evaluation:

Time taken for key generation, encryption, decryption
Key, signature, and ciphertext sizes
Graphical comparison of results
🧪 Test Environment:

Includes benchmarking support for mobile platforms (Snapdragon, Apple M-series, etc.)
🗃️ Result Storage:

Results logged and stored in a database
History section displays results in table format
🚀 How It Works
Encryption Workflow
Enter a custom message.
System encrypts using RSA, Kyber, and Hybrid methods.
Stores and compares all results visually.
Signature Workflow
Enter a message to sign.
Signs using RSA, Dilithium, and Hybrid.
Displays signature size, time, and security comparison.
🛠️ Technologies Used
Backend
Python
Flask
liboqs / pyca
SQLite
Frontend
React.js
Tailwind CSS
Chart.js / Plotly for graphs
