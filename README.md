# 🎁 A Special Birthday Letter

A luxurious, interactive digital birthday greeting featuring a 3D gift box, a realistic emerging envelope, and a heartfelt typewriter-style letter.

## ✨ Features

- **Interactive Gift Box**: Snappy lid animation with particle bursts.
- **Realistic 3D Envelope**: Features a 180° flap flip, inner shadows, and a wax seal.
- **Typewriter Letter**: Heartfelt messages typed out with natural rhythm and a blinking cursor.
- **Ambient Effects**: 2D Canvas particles (hearts/stars) + DOM-based floating particles.
- **Background Music**: Integrated audio support with loop and volume control.

## 🚀 Setup Instructions

This is a static web project. You don't need to install any heavy dependencies.

### 1. File Preparation
Ensure you have the following files in your project directory:
- `index.html` (The core application)
- `music.mp3` (Required for the background music feature)

### 2. Running the App
For the best experience (especially for audio policies and smooth asset loading), it is recommended to run this using a local server:

- **VS Code Users**: Install the **Live Server** extension, right-click `index.html`, and select "Open with Live Server".
- **Python**: Run `python -m http.server` in the terminal and visit `localhost:8000`.
- **Node.js**: Use `npx serve .`.

*Note: Simply double-clicking `index.html` to open it in a browser may work, but some browsers block audio from playing via the `file://` protocol.*

## ✍️ Customizing the Message

You can easily change the birthday card content by editing the constants at the top of the `<script>` tag in `index.html`:

```javascript
/* Edit your message here */
const LETTER_MESSAGE = `Dear You...`;

/* Edit your signature here */
const SIGNATURE = "— With love...";
```

## 📱 Mobile Compatibility
The application is fully responsive and supports touch interactions for mobile devices.

---
*Created with ❤️ for a special day.*
