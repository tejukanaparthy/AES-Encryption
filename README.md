# AES Encryption Tool

This repository provides a command-line AES encryption and decryption tool, built with Python. The tool allows you to generate a key, encrypt files, and decrypt files using AES encryption.

## Requirements

- Python 3.x
- Install the necessary dependencies using `pip`:

    pip install -r requirements.txt

## Installation

1. Clone this repository to your local machine:

    git clone https://github.com/your-username/AES-Encryption.git

2. Navigate into the project directory:

    cd AES-Encryption

3. Install the required Python libraries:

    pip install -r requirements.txt

## Usage

### 1. Generate AES Key

To generate a random AES key, run the following command:

    python encrypt_tool.py generate-key mykey.key

This will generate an AES key and save it in the file `mykey.key`.

### 2. Encrypt a File

To encrypt a file (e.g., `input.txt`) using the generated key (`mykey.key`), run:

    python encrypt_tool.py encrypt test_files/input.txt test_files/encrypted.bin mykey.key

This will encrypt the `input.txt` file and save the result in `test_files/encrypted.bin`.

### 3. Decrypt a File

To decrypt an encrypted file (e.g., `encrypted.bin`) using the AES key (`mykey.key`), run:

    python encrypt_tool.py decrypt test_files/encrypted.bin test_files/decrypted.txt mykey.key

This will decrypt `encrypted.bin` and save the output in `test_files/decrypted.txt`.

## Directory Structure

The basic directory structure of the project is as follows:

    AES-Encryption/
    │
    ├── encrypt_tool.py           # The main encryption/decryption script
    ├── requirements.txt          # List of dependencies
    ├── test_files/               # Folder containing test files
    │   ├── input.txt             # Sample input file for encryption
    │   ├── encrypted.bin        # Encrypted file (output)
    │   └── decrypted.txt        # Decrypted file (output)
    ├── README.md                # This file


## Contributing

Feel free to fork this repository and submit pull requests for any improvements or bug fixes.

