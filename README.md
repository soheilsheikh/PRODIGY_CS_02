# 🔐 Image Encryption with XOR Cipher

![encrypted-file](https://github.com/soheilsheikh/PRODIGY_CS_02/assets/96125177/ec6d5eff-798d-47de-b940-6d7f9b2d8b1d)

## 📋 Overview
This Python implementation demonstrates a basic image encryption algorithm using the XOR cipher technique. It employs symmetric key cryptography, where identical keys are used for both encryption and decryption operations.

## 🔍 Detailed Functionality

### 1️⃣ Input and Initialization
* 📁 The program prompts users for the image file path to be encrypted
* 🔑 Users must provide a numerical encryption key for the XOR operation

### 2️⃣ Encryption Process
* 📂 Opens the target image in read-binary mode (`'rb'`)
* 📊 Reads the complete image content into memory
* 🔄 Converts image data into a byte array for byte-level manipulation

![Byte Array Representation](https://github.com/soheilsheikh/PRODIGY_CS_02/assets/96125177/191121f8-ad48-467c-b4c9-816fbfec789a)

* ⚙️ Performs a bitwise XOR operation on each byte using the provided encryption key
* 🔀 The XOR operation effectively scrambles the image data by flipping bits according to the key pattern

### 3️⃣ Output Generation
* 💾 Writes the encrypted byte array back to the original file location
* ✅ Displays a confirmation message upon successful encryption

### 4️⃣ Security Considerations
* ⚠️ This represents a basic encryption implementation; more sophisticated algorithms are recommended for high-security applications
* 🔄 Decryption requires performing the XOR operation again with the identical key
* 🛡️ The current implementation lacks robust error handling mechanisms
* 💡 Future improvements could include validation for file paths and encryption key inputs

## 🚀 Getting Started
```python
# Clone this repository
git clone https://github.com/soheilsheikh/PRODIGY_CS_02.git

# Navigate to the project directory
cd PRODIGY_CS_02

# Run the encryption script
python encrypt.py
```

## 📝 License
[MIT](https://choosealicense.com/licenses/mit/)
