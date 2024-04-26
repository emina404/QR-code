# QR-code

This Node.js script is designed to streamline the process of generating QR codes for URLs. It leverages the `inquirer` package for user input, prompting users to enter a URL of their choice. The entered URL is then used to create a QR code image using the `qr-image` package.

 The generated QR code image is saved as `qr_img.png`,  while the URL itself is stored in a text file named `URL.txt` within the same folder. The `fs` module facilitates file system operations, handling the creation of files and writing data to them. This script provides a convenient way to quickly generate QR codes for URLs and store relevant information for reference, making it useful for various applications requiring QR code generation and management.
