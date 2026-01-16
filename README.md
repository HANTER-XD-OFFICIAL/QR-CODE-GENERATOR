# 📱 RASEL QR STUDIO

**RASEL QR STUDIO** is a mobile-first QR Code Generator web application designed to provide a **native mobile app–like experience** using modern web technologies.

The entire system is built using **pure HTML, CSS, and Vanilla JavaScript** and runs from a **single HTML file**, with no external frameworks required.

---

## ✨ Features

- 🔤 Generate QR Codes from text input
- 🎨 Random animated gradient background on each generation
- 👀 Live QR Code preview
- ⬇️ One-tap QR Code download
- 🕘 QR Code history storage
- 💾 Uses Browser LocalStorage for data persistence
- 🧑 User profile name and profile picture support
- 📱 Mobile-optimized UI (touch-friendly)
- 🚀 Progressive Web App (PWA) support
- 🏠 Add to Home Screen functionality
- 🧭 Fullscreen standalone mode (no browser URL bar)
- 🌐 Offline UI support (QR generation requires internet)

---

## 🧠 How It Works

### 1️⃣ QR Code Generation
QR codes are generated using the **GOQR / QRServer public API**.

API format used:https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=YOUR_TEXT

When the user enters text and taps **Generate QR**:
- The text is URL-encoded
- The QR image is generated via the API
- The QR code is displayed instantly in the preview area

---

### 2️⃣ Random Background System
- Uses JavaScript `Math.random()`
- Colors are generated using the **HSL color model**
- Each QR generation triggers a new animated gradient background

---

### 3️⃣ History System
- Every generated QR code URL is saved in **LocalStorage**
- Previously generated QR codes can be:
  - Previewed
  - Viewed again
  - Downloaded anytime
- Data persists even after app reload or browser restart

---

### 4️⃣ Profile System
- Users can upload a profile picture
- Users can set a display name
- Profile data is stored in LocalStorage
- Data remains saved across sessions

---

### 5️⃣ Mobile App Experience (PWA)
This project uses **Progressive Web App (PWA)** features:

- Inline Web App Manifest
- `display: standalone`
- `mobile-web-app-capable` enabled

As a result:
- No browser address bar is shown
- App opens in fullscreen mode
- Launches directly from the home screen
- Feels like a native Android application

---

## 🛠 Technologies Used

- HTML5
- CSS3 (Glassmorphism, animations, gradients)
- Vanilla JavaScript
- GOQR / QRServer API
- Browser LocalStorage
- Progressive Web App (PWA)

---

## 📂 Project Structure
---

## 🚀 How to Use

1. Open the HTML file in a mobile browser (Chrome recommended)
2. Open browser menu (three dots)
3. Select **Add to Home Screen**
4. Launch the app from the home screen
5. Enter text and generate QR codes

---

## 👨‍💻 Author Information

**Project Name:** RASEL QR STUDIO  
**Created By:** MD RASEL  
**Role:** Concept, UI Design, Development  
**Platform:** Web / Mobile (PWA)

All core ideas, structure, customization, and branding are created and maintained by **MD RASEL**.

---

## ⚠️ Disclaimer

- QR code generation depends on a third-party API (QRServer)
- API availability may change in the future
- Internet connection is required to generate QR codes
- Offline mode supports UI and saved data only

---

## 📜 License

This project is intended for personal and educational use.  
You are free to modify, customize, and extend it for your own projects.

---

## ⭐ Credits

- QR Code API: GOQR / QRServer
- UI Concept & Branding: MD RASEL

---

## ⚠️ Disclaimer

This project is intended for **educational and personal use only**.  
Do not use temporary email services for illegal or abusive activities.

---
## 👨‍💻 Developer

**Name:** MD RASEL  
**Branding:** Powered by MD RASEL  

<p align="left">
  <a href="https://www.facebook.com/MD.RASEL.8.2.3.4" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-Profile-1877F2?style=for-the-badge&logo=facebook&logoColor=white" />
  </a>
</p>

---

## 📞 Contact

<p align="left">
  <a href="https://wa.me/8801882278234" target="_blank">
    <img src="https://img.shields.io/badge/WhatsApp-Chat-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
  </a>

  <a href="https://www.facebook.com/MD.RASEL.8.2.3.4" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-Message-4267B2?style=for-the-badge&logo=messenger&logoColor=white" />
  </a>
</p>

---

## ⬇️ Download

<p align="left">
  <a href="https://github.com/HANTER-XD-OFFICIAL/QR-CODE-GENERATOR/releases/tag/QR-CODE_PRO" target="_blank">
    <img src="https://img.shields.io/badge/Download-App-FF5722?style=for-the-badge&logo=android&logoColor=white" />
  </a>
</p>

> 🔧 **Note:**  
> Replace `https://github.com/HANTER-XD-OFFICIAL/QR-CODE-GENERATOR/releases/tag/QR-CODE_PRO` with your app download URL  
> (APK / Website / Play Store / Direct link)

---
## 🌍 Open Website

<p align="left">
  <a href="https://hanter-xd-official.github.io/QR-CODE-GENERATOR/" target="_blank">
    <img src="https://img.shields.io/badge/Open-Website-6200EA?style=for-the-badge&logo=googlechrome&logoColor=white" />
  </a>
</p>

---
