<div align="center">

# ⚡ Shan's CheetCode

### Your Real-Time AI Interview & Meeting Copilot

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)
[![Electron](https://img.shields.io/badge/Electron-30.x-47848F?logo=electron&logoColor=white)](https://www.electronjs.org/)
[![Gemini](https://img.shields.io/badge/Gemini_2.5_Flash-Native_Audio-4285F4?logo=google&logoColor=white)](https://ai.google.dev/)
[![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows%20%7C%20Linux-lightgrey)]()

<br/>

> **A stealth desktop overlay that listens, watches, and thinks — in real time.**
> Captures system audio + screen, understands context through Gemini's native multimodal AI,
> and delivers instant, actionable answers right on your screen.

<br/>

</div>

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| **Live AI Assistance** | Powered by Gemini 2.5 Flash with native audio understanding — no separate transcription step |
| **System Audio Capture** | Hears everything your speakers play (interviewer's voice, meeting audio, presentations) |
| **Screen Analysis** | Reads your screen for additional context — code editors, slides, documents |
| **Stealth Overlay** | Frameless, always-on-top, click-through transparent window |
| **Multiple Profiles** | Interview · Sales Call · Business Meeting · Presentation · Negotiation |
| **Local AI Mode** | Fully offline with Ollama + Whisper — no data leaves your machine |
| **Cross-Platform** | macOS, Windows, and Linux support |

---

## 🚀 Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/Shantanu-9901/Shans-CheetCode.git
cd Shans-CheetCode

# 2. Install dependencies
npm install

# 3. Launch
npm start
```

**First run:**
1. Grab a free Gemini API key from [Google AI Studio](https://aistudio.google.com/apikey)
2. Paste it in the app
3. Pick your profile & language
4. Hit **Start Session** — done.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + ←↑→↓` | Move overlay window |
| `Ctrl/Cmd + M` | Toggle click-through mode |
| `Ctrl/Cmd + \` | Close window / Go back |
| `Enter` | Send a text message to AI |

---

## 🎧 Audio Capture

| Platform | Method |
|----------|--------|
| **macOS** | SystemAudioDump (built-in binary, requires macOS 15+) |
| **Windows** | Loopback audio via `getDisplayMedia` |
| **Linux** | Microphone input |

---

## 🛠️ Tech Stack

- **Framework** — Electron 30
- **AI Engine** — Google Gemini 2.5 Flash (native audio preview)
- **UI** — LitElement web components
- **Local AI** — Ollama + Whisper (optional)
- **Build** — Electron Forge

---

## 📋 Requirements

- macOS 13+ / Windows 10+ / Linux
- [Node.js](https://nodejs.org/) 18+
- Gemini API key (free tier works)
- Screen recording & microphone permissions

---

## 🔒 Privacy

- **BYOK (Bring Your Own Key)** — your API key, your data
- **Local mode available** — run fully offline with Ollama
- **No telemetry** — zero data collection, no analytics, no tracking
- Audio is streamed directly to Gemini and never stored

---

## 📄 License

Released under the [GPL-3.0 License](LICENSE).

---

<div align="center">

**Built with ❤️ by Shantanu**

</div>
