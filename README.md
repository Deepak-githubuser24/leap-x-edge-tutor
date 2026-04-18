# leap-x-edge-tutor
Offline Voice-First AI Tutor for Rural India | AMD Slingshot 2026  | Fully offline STT + TTS + Skilling
# LEAP X — Voice AI Tutor for Rural India

**AMD Slingshot 2026 National Shortlisted Project**

LEAP X helps rural students learn by speaking naturally in their own language. The AI listens, understands, gives simple explanations and quizzes, and speaks back in the same language.

### Live Voice Demo
Try the interactive demo directly in your browser:

[→ Open Live Voice Demo](https://github.com/Deepak-githubuser24/leap-x-edge-tutor/blob/main/index.html)

**Supported Languages:** Tamil, English, Hindi, Telugu, Kannada, Malayalam, Bengali, Marathi, Gujarati, Punjabi

### Technology Stack
- **Frontend**: React (TypeScript)
- **Voice Input (STT)**: Browser Speech Recognition API (with future Whisper integration)
- **AI Response**: Grok / OpenAI API (multi-language support)
- **Voice Output (TTS)**: Browser Speech Synthesis API (with future Indic TTS)
- **Future Offline**: AMD Ryzen AI NPU + Whisper + Indic TTS + quantized small LLMs

### AMD Advantage
LEAP X is designed to run efficiently on **AMD Ryzen AI NPU** for low-power, offline inference in the final version — delivering <1s responses with 50% less power consumption.

### Quick Start
```bash
git clone https://github.com/Deepak-githubuser24/leap-x-edge-tutor.git
cd leap-x-edge-tutor
npm install
npm start
