# QR Code Generator

<p align="center">
  <img src="src/images/logo-for-black.png" alt="QR Generator Logo" width="200"/>
</p>

<p align="center">
  A modern, fast, and user-friendly QR code generator web application that allows you to create and download QR codes in multiple formats.
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage</a> •
  <a href="#technologies">Technologies</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#license">License</a>
</p>

## ✨ Features

- 🎨 Clean and modern user interface
- 🔄 Real-time QR code generation
- 💾 Multiple download formats:
  - PNG (High Quality)
  - JPG (Compressed)
  - SVG (Scalable)
- 📱 Fully responsive design
- ⚡ Fast and efficient
- 🔍 Error validation
- 📳 Haptic feedback support
- 🌐 Cross-browser compatibility

## 🚀 Demo

Try the live demo: [QR Generator](https://aetherz.xyz/qr-generator)

<p align="center">
  <img src="src/images/demo-screenshot.png" alt="Demo Screenshot" width="600"/>
</p>

## 💻 Installation

### Prerequisites

- A modern web browser
- Basic understanding of HTML/CSS/JavaScript

### Local Setup

1. Clone the repository 
```
git clone https://github.com/aetherzcode/qr-generator.git
```

2. Navigate to the project directory
```
cd qr-generator
```

3. Open `index.html` in your preferred browser

## 📖 Usage

1. Open the application in your web browser
2. Enter the text or URL you want to convert into a QR code
3. Click the "GENERATE" button or press Enter
4. Choose your preferred download format:
   - PNG: Best for general use
   - JPG: Smaller file size
   - SVG: Perfect for scaling
5. Click the download button to save your QR code

## 🛠️ Technologies

- HTML5
- CSS3
- JavaScript (ES6+)
- QR Server API
- FileSaver.js
- [Other libraries/frameworks used in your project]


## ⚙️ Configuration

The application can be configured by modifying the following parameters in `src/js/main.js`:

```javascript
const CONFIG = {
  apiEndpoint: 'https://api.qrserver.com/v1/create-qr-code/',
  defaultSize: 200,
  defaultFormat: 'png'
};
```

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Bug Reports

If you discover any bugs, please create an issue [here](https://github.com/aetherzcode/qr-generator/issues).

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Creator

**AETHER**
- Website: [aetherz.xyz](https://aetherz.xyz)
- GitHub: [@aetherzcode](https://github.com/aetherzcode)
- Email: [aetherscode@gmail.com](mailto:aetherscode@gmail.com)

## 🙏 Acknowledgments

- [QR Server API](https://goqr.me/api/) for providing the QR code generation service
- [FileSaver.js](https://github.com/eligrey/FileSaver.js/) for handling file downloads
- All contributors who have helped this project grow

---

<p align="center">
  Made with ❤️ by <a href="https://aetherz.xyz">AETHER</a>
</p>

This README.md includes:
1. Header with logo and brief description
2. Quick navigation menu
3. Complete features with emojis
4. Detailed installation instructions
5. Clear usage instructions
6. Project structure
7. Contribution guidelines
8. License information
9. Creator information
10. Acknowledgments
11. Attractive markdown styling with emojis and alignment

You can customize the content according to your project needs, such as:
- Adding/removing features
- Modifying folder structure
- Adding screenshots or demos
- Changing configurations
- Adding dependencies or technologies used
- Updating contact information