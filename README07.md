# REPORT 🛡️
### Real-time Evidence Processing for Official Record Transcription

> "Speak in any of India's 22 languages — REPORT builds your case."

Built for **HackIndia 2K26** | Mailam Engineering College | Tamil Nadu Police AI System

---

## 🚨 The Problem

Only **1 in 3 crimes** are formally reported in India.

Language barriers, trauma, and complex forms stop victims from speaking up.
Police forms are in English. Victims speak Tamil, Hindi, or regional languages.
Sketch artists take hours. FIR filing is slow and intimidating.

---

## ✅ The Solution

REPORT is the world's first AI crime reporting system that works across
all 22 official Indian languages — fully voice-driven, no typing required.

| Step | What Happens |
|------|-------------|
| 🎙 Speak | Victim speaks in their language |
| 🧠 AI Understands | GPT-4o extracts suspect details, location, timeline |
| 🎨 Scene Rebuilt | AI generates suspect sketch + crime scene map |
| 📄 FIR Generated | Bilingual FIR in Tamil Nadu Police format |

---

## ✨ Features

- 🌐 **22 Indian Languages** — Hindi, Tamil, Telugu, Bengali, Urdu + 17 more
- 🔄 **RTL Support** — Urdu, Kashmiri, Sindhi right-to-left rendering
- 🎙 **Voice Recording** — Whisper AI transcription with language auto-detect
- 🧠 **AI Extraction** — GPT-4o extracts 18+ FIR fields from natural speech
- 🎨 **AI Suspect Sketch** — Auto-generated composite from voice description
- 🗺 **Crime Scene Map** — Top-down SVG layout with escape route
- 📄 **FIR PDF** — Official Tamil Nadu Police format, bilingual output
- 📋 **FIR History** — Save, search and manage all past FIRs
- ⌨️ **Manual Mode** — Text input fallback when mic is unavailable

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React + Base44 |
| Speech-to-Text | OpenAI Whisper |
| AI Extraction | GPT-4o / Gemini |
| Sketch Generation | Pollinations AI (free) |
| FIR Document | jsPDF |
| Storage | localStorage |

---

## 🚀 Live Demo

🔗 **[kavalan-report-shield.base44.app](https://kavalan-report-shield.base44.app)**

---

## 🏃 Run Locally
```bash
git clone https://github.com/yourusername/report-app
cd report-app
npm install
# Add your OpenAI key to .env
echo "VITE_OPENAI_API_KEY=sk-your-key" > .env
npm run dev
```

---

## 👥 Team

| Role | Responsibility |
|------|---------------|
| Speech AI Engineer | Whisper integration, audio pipeline |
| NLP & LLM Engineer | GPT-4o prompting, JSON extraction |
| Computer Vision Dev | Sketch generation, scene mapping |
| Frontend & Presenter | UI, FIR PDF, demo delivery |

**Institution:** Mailam Engineering College, Tamil Nadu
**Event:** HackIndia 2K26 — 14 March 2026

---

## 📜 License

MIT License — free to use, modify and distribute.

---

> *"Current systems record what happened. REPORT helps victims finally be heard."*
```

---

## GitHub Topics to Add
In the **Topics** field on GitHub add these tags:
```
ai police tamil-nadu crime-reporting whisper-ai gpt4 fir india multilingual react hackathon
