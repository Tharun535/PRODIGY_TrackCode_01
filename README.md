# PRODIGY_TrackCode_01
CipherCLI is a simple yet powerful command-line tool that allows users to encrypt and decrypt messages using the Caesar Cipher algorithm. With a user-friendly interface and interactive prompts, this tool makes encryption and decryption effortless.

📌 Features
✅ Encrypt and Decrypt Messages – Secure your text with a shift-based cipher.
✅ User-Friendly CLI – Simple, interactive, and easy to use.
✅ Colorful and Engaging Interface – Uses colorama for enhanced visuals.
✅ Input Validation – Ensures only valid text and numeric shift values are entered.
✅ Cross-Platform Support – Works on Windows, macOS, and Linux.

🛠️ Installation
Before using CipherCLI, you need to install Python (3.x recommended) and the required dependencies.

1️⃣ Install Python (if not already installed)
Check if Python is installed:

python --version
If not installed, download it from python.org.

2️⃣ Install Dependencies
CipherCLI uses colorama for CLI color enhancements. Install it using:

pip install colorama
🚀 Usage
Run the script
Save the script as CipherCLI.py and execute it from the terminal:

python CipherCLI.py
🔹 Encrypt a Message
Choose e for encryption.
Enter your message (e.g., "Hello, World!").
Input a shift value (1-25).
The encrypted result will be displayed.
Example:

Enter your choice (e/d): e
Enter your message: Hello, World!
Enter shift value (1-25): 3
✅ Result: Khoor, Zruog!
🔹 Decrypt a Message
Choose d for decryption.
Enter the encrypted text.
Input the same shift value used for encryption.
The decrypted message will be displayed.
Example:

Enter your choice (e/d): d
Enter your message: Khoor, Zruog!
Enter shift value (1-25): 3
✅ Result: Hello, World!
📌 How It Works
CipherCLI uses the Caesar Cipher algorithm, a simple shift-based encryption method where each letter in the plaintext is shifted by a fixed number of positions in the alphabet.

Example with a shift of 3:

A → D, B → E, C → F, ..., X → A, Y → B, Z → C
Why is it useful?
✅ A great way to learn cryptography basics.
✅ Helps understand encryption principles in a simple, visual way.
✅ Can be used for basic text obfuscation or fun cryptography projects.

💡 Contributing
Contributions are welcome! Feel free to fork the repo, create new features, or report issues.

📜 License
This project is licensed under the MIT License – free to use, modify, and distribute.

🎉 Enjoy Encrypting & Decrypting with CipherCLI! 🚀

