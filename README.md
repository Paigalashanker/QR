A simple, client-side QR Code Generator built using HTML, CSS, and JavaScript.
The generated QR code embeds the input text directly, allowing it to be scanned offline without any server interaction.

🔹 Features

Generate QR codes from plain text

Fully static (no backend, no database)

Works on GitHub Pages

QR codes are offline-readable

Clean and minimal UI

🔹 How It Works

User enters text in the input field

JavaScript generates a QR code using a standard QR encoding library

The QR code directly contains the text data

When scanned, the text is decoded and displayed by the scanner

📌 No data is stored or sent over the internet after generation.

🔹 Tech Stack

HTML – Structure

CSS – Styling

JavaScript – Logic

QRCode.js – Open-source library for QR encoding

The QR generation happens entirely in the browser.

🔹 Why a Library Is Used

QR code generation involves standardized encoding, error correction, and masking.
Instead of reimplementing this complex logic, a trusted open-source library is used — which is a standard industry practice.

🔹 Live Demo

👉 (Add your GitHub Pages link here)

https://your-username.github.io/qr-generator/

🔹 Usage

Open the website

Enter any text

Click Generate

Scan the QR code

The original text will be displayed

You can scan the QR even with mobile data and Wi-Fi turned off.

🔹 Project Type

Static Web Application

Client-side QR Encoding

No server dependency

🔹 Possible Enhancements

Download QR as image

Encryption support

Error correction selection

Mobile-first UI

Offline-first local hosting of library

🔹 License

This project uses open-source libraries and is free for educational use.
