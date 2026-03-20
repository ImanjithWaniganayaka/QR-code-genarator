# 📱 QR Code Generator (Python)

A simple and lightweight QR Code Generator built using Python. This program allows users to input any URL and generates a QR code image instantly.

## 🚀 Features

- Generate QR codes from any URL
- Saves QR code as an image (`.png`)
- Simple and beginner-friendly code
- Uses Python `qrcode` library

## 🛠️ Technologies Used

- Python 3
- qrcode
- Pillow (PIL)

## 📦 Installation

Make sure Python is installed on your system.

1. **Clone the repository**

```bash
git clone https://github.com/ImanjithWaniganayaka/QR-code-genarator
cd qr-code-generator
```

2. **Install dependencies**

```bash
pip install qrcode[pil]
```

## ▶️ Usage

Run the script:

```bash
python main.py
```

Enter a URL when prompted:

```
Enter the URL: https://example.com
```

The QR code will be generated and saved as:

```
qrcode.png
```

## 📁 Project Structure

```
qr-code-generator/
│
├── main.py        # Main script
├── README.md      # Project documentation
```

## 🧠 How It Works

- Takes user input (URL)
- Generates a QR code using `qrcode`
- Saves the QR image using Pillow

## 📌 Example

Input:

```
https://google.com
```

Output:

```
qrcode.png (QR Code Image)
```

## 🔮 Future Improvements

- Add custom colors
- Add logo inside QR code
- GUI version (Tkinter / Web App)
- Download as SVG format

## 🤝 Contributing

Feel free to fork this repo and improve it. Contributions are welcome!

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

Created by **Imanjith**
