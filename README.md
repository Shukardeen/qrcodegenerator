# QR Code Generator

A web application that generates QR codes from text or URLs with a beautiful user interface. Built with vanilla HTML, CSS, and JavaScript.

![QR Code Generator](https://img.shields.io/badge/QR%20Code-Generator-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## ✨ Features

- **Instant QR Code Generation**: Generate QR codes from any text or URL
- **Modern UI/UX**: Clean, responsive design with smooth animations
- **Download Functionality**: Save generated QR codes as images
- **Real-time Preview**: See your QR code immediately after generation
- **Cross-platform**: Works on desktop and mobile devices
- **No Dependencies**: Pure vanilla JavaScript implementation

## 📸 Screenshots

### Main Interface
![Main Interface](screenshots/main-interface.png)

### QR Code Generated
![QR Generated](screenshots/qr-generated.png)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and animations
- **JavaScript (ES6+)**: Dynamic functionality and API integration
- **QR Server API**: External API for QR code generation
- **Google Fonts**: Inter font family for typography

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/qr-code-generator.git
   cd qr-code-generator
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser

3. **Start generating QR codes!**

## 🎯 Usage

1. **Enter Text or URL**: Type any text or URL in the input field
2. **Generate QR Code**: Click the "Generate QR Code" button
3. **View Result**: The QR code will appear in a popup window
4. **Download**: Click "Download QR" to save the image
5. **Close**: Click "Close" to return to the main interface

## 📁 Project Structure

```
qr-code-generator/
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── app.js              # JavaScript functionality
├── Images/             # Image assets
│   ├── icon.jpg        # Favicon
│   ├── qrBg.jpg        # Background image
│   └── qrpng.png       # QR icon
└── README.md           # This file
```

## 🔧 How It Works

The application uses the [QR Server API](https://api.qrserver.com/) to generate QR codes:

1. **Input Validation**: Checks if the user has entered text or URL
2. **API Call**: Sends the input to the QR Server API
3. **Image Generation**: Creates a 150x150 pixel QR code
4. **Display**: Shows the generated QR code in a modal popup
5. **Download**: Allows users to download the QR code as a JPG file

## 🎨 Features in Detail

### User Experience
- Input validation with helpful error messages
- Loading states and visual feedback
- Intuitive button interactions with hover effects

### QR Code Options
- Supports any text input
- Handles URLs, contact information, WiFi credentials, etc.
- High-quality image output

## 🙏 Acknowledgments

- [QR Server API](https://api.qrserver.com/) for QR code generation
- [Google Fonts](https://fonts.google.com/) for the Inter font family
- [Inter Font](https://rsms.me/inter/) by Rasmus Andersson

---

⭐ If you found this project helpful, please give it a star! 
