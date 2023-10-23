# Caesar-Cipher

A simple Caesar cipher encryption and decryption tool implemented using JavaScript, HTML, and CSS. The Caesar cipher is a substitution cipher that shifts each letter in the plaintext by a fixed number of positions down the alphabet.

## Features

- Encode and decode messages using the Caesar cipher.
- Customizable shift value and alphabet length (modulo).
- Options to maintain case, convert to lowercase, or convert to uppercase.
- Option to remove or ignore foreign characters (non-alphabetic characters).

## Getting Started

### Prerequisites

To use this tool, you need a modern web browser that supports JavaScript.

### Installation

1. Clone the repository or download the source code.
   ```sh
   git clone https://github.com/your-username/caesar-cipher.git
   ```
2. Navigate to the project directory.
   ```sh
   cd caesar-cipher
   ```
3. Open the `index.html` file in your web browser.

## Usage

1. Select the desired operation: "Encode" or "Decode".
2. Enter the shift value (number of positions to shift).
3. Enter the modulo value (length of the alphabet).
4. Enter the custom alphabet you want to use.
5. Select the letter case option: maintain case, lowercase, or uppercase.
6. Select the foreign characters option: remove or ignore.
7. Enter the text you want to encrypt or decrypt in the input field.
8. Click the "Submit" button.
9. The result will be displayed in the output section.

## Examples

### Encryption
To encrypt the message "HELLO" with a shift of 3:
- Input: "HELLO"
- Shift: 3
- Output: "KHOOR"

### Decryption
To decrypt the ciphertext "KHOOR" with a shift of 3:
- Input: "KHOOR"
- Shift: 3
- Output: "HELLO"

## Project Structure

- `index.html`: The HTML file containing the user interface.
- `style.css`: The CSS file for styling the user interface.
- `caesar.js`: The JavaScript file containing the Caesar cipher algorithm.
- `README.md`: The readme file with instructions and information about the project.

