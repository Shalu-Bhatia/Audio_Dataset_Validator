---
title: Audio Dataset Validator
emoji: 🎚️
colorFrom: indigo
colorTo: purple
sdk: docker
app_file: Dockerfile
app_port: 7860
pinned: false
---

# 🎚️ Audio Dataset Validator

> A professional-grade audio quality analysis & cleaning tool for **TTS** and **ASR** dataset creators.

**Live Demo** → [HuggingFace Spaces](https://huggingface.co/spaces/ShaluBhati/Diploma_Project_Audio_Dataset_Validator)  |  **Docs** → [DOCUMENTATION.md](./DOCUMENTATION.md)

---

## � What It Does

Upload audio files and instantly get:
- ✅ **Quality Analysis** — sample rate, channels, bit depth, RMS, peak amplitude
- 🔍 **Issue Detection** — silence, clipping, low volume, DC offset, stereo
- � **Health Score** — 0–100 rating per file
- 🤖 **AI Auto-Clean** — one-click fix with research-standard parameters
- 🌊 **4 Waveform Modes** — Waveform, Bars, Mirror, Spectrogram
- � **Export** — download cleaned WAV + JSON/CSV reports

---

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/Shalu-Bhatia/Audio_Dataset_Validator.git
cd Audio_Dataset_Validator
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run Locally

```bash
npm run dev
```

Open **http://localhost:3000** in your browser.

---

## � Run with Docker

```bash
docker build -t audio-validator .
docker run -p 7860:7860 audio-validator
```

Open **http://localhost:7860**

---

## 🎯 How to Use

1. **Drag & drop** audio files (WAV, MP3, FLAC, OGG)
2. **View** instant analysis results and health score per file
3. **Click AI Auto-Clean** to automatically fix issues, or adjust settings manually
4. **Download** the processed WAV file or export the analysis report

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | Next.js 14 + TypeScript |
| Audio Engine | Web Audio API |
| UI | Tailwind CSS + Framer Motion |
| Visualization | WaveSurfer.js + Recharts + Canvas |
| Deployment | Docker / HuggingFace Spaces |

---

## 📋 Requirements

- **Node.js** v18+
- **npm** v9+

---

## 👤 Author

Built by [Shalu-Bhatia](https://github.com/Shalu-Bhatia/Audio_Dataset_Validator)
