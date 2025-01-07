# QR Code Generator

Welcome to the **QR Code Generator** project! This simple Node.js application allows users to convert a website link (URL) into a QR code. The URL entered by the user is saved in a text file (`URL.txt`), and the corresponding QR code is generated as a `.png` file (`qr_img.png`).

## 🚀 Features

- **User Input**: Prompts the user to enter a URL.
- **QR Code Generation**: Converts the entered URL into a QR code image.
- **File Saving**:
  - Saves the URL in a `URL.txt` file.
  - Saves the QR code as a `qr_img.png` file.

## 🖥 Technologies Used

This project utilizes the following technologies:

- **Node.js**: JavaScript runtime environment.
- **Inquirer**: CLI package for asking user input.
- **qr-image**: Used to generate a QR code from the provided URL.
- **fs**: Native Node.js module for file system operations.

## 📦 Prerequisites

Make sure you have the following installed before running the project:

- **Node.js** (LTS version is recommended): [Download Node.js](https://nodejs.org/)
- **npm**: The Node.js package manager (it comes with Node.js installation)

## 🏁 Installation

Follow these steps to get the project up and running:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Krishnasai8500/2.4-qr-code-project.git
   cd 2.4-qr-code-project
   ```

2. **Install the dependencies**:
   ```bash
   npm install
   ```

## 🎬 Usage

Run the application:
```bash
node index.js
```

Enter the URL when prompted by the terminal.

Upon entering the URL:
- The URL will be saved to a file named `URL.txt`
- A QR code image corresponding to the URL will be saved as `qr_img.png`

## 💡 Example

Here's an example of how the program works:

```bash
$ node index.js
Type in your URL: https://example.com
The file has been saved!
```

After the process is complete, you will see two new files in your project directory:
- **URL.txt**: Contains the URL you entered
- **qr_img.png**: The generated QR code image for the entered URL

## 🔧 Dependencies

This project uses the following dependencies:
- **inquirer**: ^9.3.7 — Interactive CLI prompts for user input
- **qr-image**: ^3.2.0 — Converts the URL into a QR code image
- **fs**: Built-in Node.js module for file system operations

## 📄 License

This project is licensed under the **ISC License**. See the LICENSE file for more details.

## ✅ You're all set! Happy QR Code Generating!
