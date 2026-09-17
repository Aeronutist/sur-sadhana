# 🎼 Sur Sadhana — Free Indian Classical Riyaz Tool

**Sur Sadhana** is a free, browser-based practice tool that helps you improve your pitch accuracy on the pure swaras:

**सा रे गा मा प ध नि सां**

No installation • No account • No payment  
Just open and start your daily riyaz!

---

## ✨ Features

- Real-time pitch detection using your microphone
- Vertical Pitch Needle (moves up = too high, down = too low)
- Clear Hindi guidance messages (“सुर ऊपर उठाइए”, “सुर नीचे लाइए”)
- Live cents display (+18¢ / –22¢) + stability indicator
- Color feedback: 🟢 Correct • 🟡 Close • 🔴 Needs correction
- Score system + High score + Session summary
- Male / Female / Custom Sa (Hz) selection
- One-click “🎤 अपना सा गाइए” calibration
- Beautiful dark UI with live frequency visualizer
- 100% client-side — your voice never leaves your device

---

## 🌐 Free Live Demo

Try it instantly here:

**Live Website:** [click here](https:/Aeronutist.github.io/sur-sadhana/)


---

## 📥 Download

- Click the green **Code** button → **Download ZIP**
- Or download the single file: [`index.html`](index.html)

---

## 🚀 How to Run Locally

1. Download `index.html`
2. Open it in Chrome / Edge / Firefox

**Important Note about Microphone:**  
Modern browsers block the microphone on `file://` links.  
Use one of these methods:

**Method A (Easiest):**
```bash
python -m http.server 8000
📖 How to PracticeSelect your voice type (Male / Female / Other)
Set your Sa frequency or click “🎤 अपना सा गाइए”
Press START
Sing the shown swara clearly and steadily
Watch the vertical needle and Hindi messages
Press ■ रोकें anytime to see your session summary

There is no game over — practice as long as you want!


🛠️ Technical DetailsSingle pure HTML file (no frameworks, no build step)
Pitch detection: YIN algorithm (Web Audio API)
Tuning: Just Intonation (traditional Indian ratios)
Tolerance: ±15 cents (green) / ±35 cents (yellow)

📜 LicenseThis project is released under the MIT License.You are free to use, modify, share, and even use it commercially.
Just keep the original copyright notice.

🙏 CreditsMade with ❤️ for every student who wants to improve their sur.Shubh Riyaz! 🎤✨



