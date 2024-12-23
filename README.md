QRCode_Generator
This is a simple Node.js application that generates a QR code from a user-provided URL and saves it as an image file. Additionally, the application stores the URL in a text file for reference.

Features
Interactive Input: Prompts the user to input a URL.
QR Code Generation: Converts the provided URL into a QR code and saves it as qr_img.png.
URL Storage: Saves the input URL in a text file named URL.txt for future reference.
Prerequisites
Ensure the following are installed on your system:

Node.js: JavaScript runtime environment.
npm: Node.js package manager (comes bundled with Node.js).

Usage
Run the application: node index.js
Provide a URL when prompted.

Check the outputs:

qr_img.png: The QR code image representing the URL.
URL.txt: A text file containing the input URL.
Dependencies
This application uses the following packages:

inquirer: For interactive user input.
qr-image: For generating QR codes.
fs: Node.js built-in module for file system operations.
