<h1 align="center">🤟 VoxaSign — Gesture Studio</h1>
<h3 align="center">AI-Powered Real-Time Sign Language → Text → Speech</h3>

<p align="center">
  <img src="https://img.shields.io/badge/TensorFlow.js-WebGL-orange?style=for-the-badge&logo=tensorflow">
  <img src="https://img.shields.io/badge/MediaPipe-Vision-green?style=for-the-badge&logo=google">
  <img src="https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge&logo=javascript">
  <img src="https://img.shields.io/badge/Edge--AI-Privacy--First-black?style=for-the-badge">
</p>

<p align="center">
  <b>Bridging Communication Gaps with Inclusive AI 🤝</b><br>
  Real-time gesture translation directly in your browser — no servers, no latency.
</p>

---

## 📌 Project Overview

**VoxaSign** is a professional **AI Gesture Translation Studio** designed to empower the Deaf and Hard of Hearing (DHH) community.

It is a **fully browser-based Edge-AI system** that delivers:

- ⚡ Real-time gesture recognition  
- 🔒 Complete privacy (on-device inference)  
- 🌐 Cross-platform accessibility  

---

## 🚀 Live Studio

👉 https://voxasign.netlify.app/

---

## ⚠️ The Problem

> 🌍 Over **70 million people** rely on sign language globally.

Communication barriers still exist in:

- 🏥 Healthcare  
- 🎓 Education  
- 🏦 Banking  

💡 **VoxaSign solves this** with a **browser-based AI translator** that works on any device.

---

## ✨ Studio Features

- 🎥 **Live Camera Mode** — Real-time hand gesture detection  
- 🖼️ **Image Upload Mode** — Analyze static ASL images  
- 🧠 **Neural Word Builder** — Convert letters into words  
- 🔊 **Speech Engine** — Instant text-to-speech output  
- 🎨 **Modern UI** — Glassmorphism + Midnight Blue theme  
- ⚡ **Real-Time Performance** — Smooth inference using WebGL  

---

## 🧠 Technical Architecture

### 🔄 AI Pipeline

```
Camera → MediaPipe → Landmark Extraction → Normalization → DNN → Text → Speech
```

---

### ⚙️ Core Components

- **Hand Tracking:** MediaPipe (21 landmarks, 63 coordinates)  
- **Normalization:** Wrist-relative scaling  
- **Model:** Dense Neural Network (TensorFlow.js)  
- **Inference:** Real-time in-browser execution  

---

## 🌐 Edge-AI Deployment

- 🔒 **Privacy-First:** No cloud, no data leaves device  
- ⚡ **Low Latency:** Instant predictions  
- 📱 **Cross-Platform:** Works on desktop & mobile  

---

## 📂 Project Structure

```
VoxaSign/
├── model/
│   ├── model.json
│   └── weights.bin
├── index.html
├── style.css
├── script.js
└── assets/
```

---

## 🚀 Quick Start

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Atiqumer/VoxaSign.git
cd VoxaSign
```

---

## 💻 Run Locally

⚠️ Camera access requires a local server

### 🪟 Windows

- Open project folder  
- Use **VS Code Live Server** (Recommended)  
OR  
- Open `index.html` (limited functionality)

---

### 🍎 macOS

```bash
python3 -m http.server 8000
```

👉 Open: http://localhost:8000  

---

### 🐧 Linux

```bash
python3 -m http.server 8000
```

👉 Open: http://localhost:8000  

---

## 📖 How It Works

1. Select mode (Camera / Upload)  
2. Show hand gesture  
3. Model predicts ASL letter  
4. Click **"Add to Word"**  
5. Click **"Speak 🔊"** for audio  

---

## ⚙️ Core Engineering Highlights

- 🎯 Wrist-relative normalization → stable predictions  
- 🔍 Confidence filtering → reduces noise  
- 🧠 Efficient memory handling (`tf.dispose`)  
- ⚡ GPU acceleration via WebGL  

---

## 📊 Dataset

| Attribute | Details |
|----------|--------|
| Name     | Synthetic ASL Alphabet |
| Classes  | 27 (A–Z + Space) |
| Source   | Kaggle |

---

## 🛤️ Roadmap

- [ ] 🧠 Sentence-level prediction (NLP)  
- [ ] 🔁 Speech → Sign translation  
- [ ] 📱 Progressive Web App (Offline Mode)  
- [ ] 🌍 Multi-language support  

---
## 🌍 Vision

> **"Bridging the Silence with AI"**

VoxaSign aims to make communication **inclusive, real-time, and accessible for everyone.**

---

## ⭐ Support

If you like this project:

- ⭐ Star the repo  
- 🍴 Fork it  
- 🧠 Contribute  
- 🐛 Report issues  

---