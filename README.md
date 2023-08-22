# Image Encryption and Decryption using XOR

This is a simple Python script that demonstrates how to perform basic image encryption and decryption using the XOR operation. Please note that this code is for educational purposes only and is not suitable for secure encryption.

## Overview

This script allows you to encrypt and decrypt image files using a provided encryption key. The code uses the XOR operation to manipulate the image data. The same key is used for both encryption and decryption. It's important to understand that XOR-based encryption is not considered secure and should not be used for actual data protection.

## How it Works

1. The script prompts the user to input the path to an image file and an encryption key for either encryption or decryption.
2. The image data is read from the specified file and converted into a byte array for easy manipulation.
3. Each byte in the image data is XORed with the encryption key to perform the encryption or decryption.
4. The modified image data is then written back to the original image file.

## Usage

1. Clone the repository to your local machine:

git clone https://github.com/Shayanvatsa/image-encryption.git

2. Navigate to the project directory:

cd image_encdec

3. Run the script using Python:

python image_encryption.py

4. Follow the prompts to provide the path to the image file and the encryption/decryption key.

## Disclaimer

This code is provided for educational purposes only. It does not provide secure encryption and should not be used for sensitive data. If you are looking for secure encryption methods, consider using established cryptographic libraries and techniques.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or fixes, feel free to open an issue or submit a pull request.
