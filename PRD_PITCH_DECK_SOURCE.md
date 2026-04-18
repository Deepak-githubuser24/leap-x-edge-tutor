# PRD: LEAP X - The Sovereign AI Tutor for Bharat
## Project Vision & Pitch Deck Specification for NotebookLM

### 1. MISSION STATEMENT
LEAP X aims to bridge the rural-urban education gap in India by providing a high-fidelity, high-agency AI tutor that works on-device, speaks local dialects, and adapts to individual mastery levels without requiring constant high-speed internet.

### 2. CORE PROBLEM (The "Why")
- **The Connectivity Gap**: Rural students lack consistent broadband, rendering cloud-only AI (like ChatGPT) unreliable.
- **The Language Barrier**: Most educational AI is English-centric; technical concepts are lost in translation.
- **The Guidance Deficit**: Passive video content doesn’t provide the active "hint-based" Socratic feedback needed for deep learning.

### 3. THE SOLUTION (LEAP X)
An "Educational Operating System" that leverages local hardware (AMD Ryzen AI) and specialized Indic Voice models (Sarvam AI) to provide a private, fast, and culturally resonant learning experience.

### 4. KEY DIFFERENTIATORS (The "Alpha")
- **Edge-AI Efficiency**: Optimized for the AMD Ryzen AI NPU, enabling complex reasoning with minimal latency.
- **Deep Dialect Support**: Not just "Hindi," but localized phonetics for 10+ languages (Tamil, Marathi, Bengali, etc.) using Sarvam AI’s Bulbul architecture.
- **Socratic Pedagogy**: The AI is programmed to never give direct answers; it provides scaffolding (hints/analogies) to build true cognitive mastery.

### 5. PRODUCT ARCHITECTURE (The Stack)
- **Intelligence**: Gemini 3 Flash (optimized for reasoning/quota efficiency).
- **Voice Performance**: Sarvam AI (Primary Indic TTS) with Gemini TTS fallback.
- **Data Persistence**: Firebase Firestore + Cloud Storage for persistent user data & modules.
- **Security**: Google Auth + Email/Password with encrypted recovery + Firestore Rules.
- **UI/UX**: React + Tailwind + Framer Motion (Modern, "AMD-inspired" industrial aesthetic).

### 6. KEY FEATURES (Pitch Deck Slides)
- **Concept Coach**: Real-time voice/text tutor with low-latency responses.
- **Multilingual Nodal Network**: Instantly switch between 10+ languages.
- **Mastery Dashboard**: Heatmaps and spider charts showing progression in STEM subjects.
- **Local NPU Status**: Live visualization of on-device processing power.
- **Offline-First Resilience**: Architecture designed to cache modules and run inference locally.

### 7. TARGET MARKET & ADOPTION
- **Primary**: K-12 students in Tier-II and Tier-III Indian cities.
- **Secondary**: Vocational training for rural youth entering technical fields.
- **B2B**: Integration with government-issued laptops and rural education NGOs.

### 8. DESIGN PHILOSOPHY (The "Vibe")
- **Colors**: AMD Vibrant Orange (#FF6321), NPU Electric Blue, Neutral Dark Grays.
- **Typography**: Inter (UI), Space Grotesk (Headers), and native script fonts (Tamil/Hindi).
- **Feel**: Sophisticated, technical yet accessible—transforming a standard laptop into a "Specialized Learning Machine."

### 9. SUCCESS METRICS
- **Latency**: Sub-500ms voice-to-logic response time.
- **Engagement**: 40% higher retention vs. video-based learning through "Active Recall."
- **Agency**: Significant reduction in "Answer Seeking" behavior in favor of "Problem Solving."

### 10. REVENUE & SUSTAINABILITY
- **Device Partnership**: Bundled with AI-capable hardware.
- **Freemium Tier**: Free core STEM subjects; premium professional skill modules.
- **Data Insights**: Aggregate (anonymized) literacy/numeracy heatmaps for policy makers.

---
### PROMPT FOR NOTEBOOK LM (COPY & PASTE)
"Using the provided LEAP X PRD and architecture details, create a 12-slide Pitch Deck for investors. 
The deck should emphasize the marriage of 'AMD Hardware' + 'Sarvam AI Voice' + 'Socratic Pedagogy' as a sovereign education solution for India. 
Structure: 
1. The Education Gap in Bharat. 
2. Introducing LEAP X. 
3. The Power of On-Device AI (AMD NPU). 
4. Multilingual Mastery (Sarvam AI). 
5. The Socratic Method vs. LLM Laziness. 
6. Product Showcase (Tutor & Dashboard). 
7. User Journey: From Rural Village to Technical Mastery. 
8. The Competitive Advantage. 
9. Business Model: Partnerships & Bundling. 
10. The Team & Philosophy. 
11. Roadmap to 100M Students. 
12. Call to Action: Join the LEAP."
