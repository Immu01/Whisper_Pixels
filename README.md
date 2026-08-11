<div align="center">

# 🕶️ Whisper Pixels

### *What you see isn't all you get*

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![No Backend](https://img.shields.io/badge/Backend-None%20Required-8b5cf6?style=for-the-badge)

**[🚀 Live Demo](https://immu01.github.io/Whisper_Pixels/)**

</div>

---

## About

**Whisper Pixels** is a browser-based steganography studio that lets you hide secret, password-encrypted messages inside everyday files — images, videos, audio, and even plain text — without anyone noticing anything is different. Everything runs entirely in your browser: no server, no uploads, no data ever leaves your device.

## ✨ Features

- 🖼️ **Image Steganography** — hides data in pixel color values using Least Significant Bit (LSB) encoding
- 🎥 **Video Steganography** — embeds encrypted payloads into video files without affecting playback
- 🎵 **Audio Steganography** — conceals messages inside audio files while preserving sound quality
- 📝 **Text Steganography** — hides messages using invisible zero-width characters between words
- 🔒 **Password Protection** — XOR-based encryption with password hash verification
- 💡 **Hint System** — optional password hints to help you recall your passphrase later
- 🌗 **Light / Dark Mode** — right-click anywhere to toggle themes
- 🎨 **Interactive UI** — animated particle background, 3D tilt effects, and smooth transitions
- 📱 **100% Client-Side** — no backend, no database, no data collection

## 🛠️ Tech Stack

![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Canvas API](https://img.shields.io/badge/-Canvas%20API-000000?style=flat-square&logo=html5&logoColor=white)

Built with vanilla HTML, CSS, and JavaScript — no frameworks, no build tools, no dependencies.

## ⚙️ How It Works

**Image/Video/Audio:** Whisper Pixels manipulates the least significant bit of pixel color channels (or appends encoded data to file bytes) — changes so small they're invisible to the eye or ear, but recoverable with the right decoder.

**Text:** Secret messages are converted to binary and encoded using invisible zero-width Unicode characters (`\u200B`, `\u200C`) inserted between words in your cover sentence — the text looks completely normal but carries hidden data.

**Encryption:** Before hiding, your message is XOR-encrypted with your password. A hash of the password is embedded alongside it so the decoder can verify the correct password was entered — without ever storing the password itself.

## 🚀 Getting Started

No installation or build step required.

```bash
git clone https://github.com/Immu01/Whisper_Pixels.git
cd Whisper_Pixels
```

Then simply open `index.html` in your browser.

## 📁 Project Structure

```
Whisper_Pixels/
├── index.html      # Landing page / showroom
├── studio.html      # Main steganography studio (encode/decode)
└── .gitignore
```

## ⚠️ Disclaimer

This project was built for **educational purposes** to demonstrate steganography concepts. The XOR-based encryption used here is simple and **not cryptographically secure** — do not use this tool to protect sensitive or high-stakes information.

---

<div align="center">

Made with 🔮 by [Imran Shaik](https://github.com/Immu01)

</div>