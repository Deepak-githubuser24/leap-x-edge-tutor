# LEAP X - Offline Voice AI Tutor

**LEAP X** is a production-grade prototype for the AMD Slingshot 2026 National Finale. It provides personalized, explainable, multilingual learning that boosts confidence and outcomes for rural Indian students.

## Key Features

1. **100% Offline Inference:** Runs PyTorch Mobile / TFLite and localized models directly on the **AMD Ryzen AI NPU (XDNA)**. No cloud dependency.
2. **Multilingual Voice-First UX:** Supports English, Hindi, and Tamil using Whisper Tiny (STT) and MeloTTS/XTTS style (TTS).
3. **Concept Coach & Mastery Tracking:** Spaced-repetition study planner with live mastery tracking.
4. **Rubric-Aware Feedback Engine:** Anti-cheat by design, and provides real-time rubric feedback on essays and code.

## Tech Stack

- **Frontend:** React 19, TypeScript, Vite, Tailwind CSS, shadcn/ui, Framer Motion
- **AI / Tutor Engine:** Gemini 3.1 Pro (simulating the local AMD NPU quantized model)
- **Voice Interactions:** WebKitSpeechRecognition (simulating Whisper Tiny) + Gemini Flash TTS (simulating local fast TTS)
- **Data Persistence:** SQLite (Firebase Auth/Firestore via AI Studio prototype layer)

## How to Run locally

This repository is ready to be cloned and tested on an AMD Ryzen AI powered system:

### 1. Requirements

- Node.js `v22+`
- AMD Ryzen CPU with integrated NPU + ROCm drivers

### 2. Setup

```bash
# Clone the repository
git clone https://github.com/your-org/leap-x.git
cd leap-x

# Install dependencies
npm install

# Setup your local environment variables (if integrating cloud fallbacks)
cp .env.example .env
```

### 3. Start Development Server

```bash
npm run dev
```
Navigate to `http://localhost:3000` to test the prototype.

---

## The "Offline" NPU Simulation
For the web-based demo format of this repository, heavy inferencing tasks (LLM answering, STT, TTS) that would typically use AMD ROCm logic on-device are abstracted. 
In the production build targeted for AMD APUs, we utilize OpenVINO / DirectML bindings to dispatch:
1. `whisper-tiny.en/hi/ta-q4.gguf` to the NPU.
2. `phi-3-mini-4k-instruct-q4.gguf` for offline reasoning.
3. Indic TTS for speech output.
