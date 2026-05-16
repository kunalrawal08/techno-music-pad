<div align="center">


# ⚡ Neon Techno Lab
### The Ultimate AI-Powered Techno Production Suite

[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=for-the-badge&logo=vercel)](https://vercel.com)
[![React 19](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-6-646CFF?style=for-the-badge&logo=vite)](https://vitejs.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)

</div>

---

## 🚀 Overview

**Neon Techno Lab** is a professional-grade, browser-based techno production environment. It combines a high-performance dual-deck sequencer with state-of-the-art AI integration to help you craft, mix, and perform techno music in real-time.

Built with **React 19**, **Vite**, and **Three.js**, it offers a zero-latency audio engine and stunning 3D visualizations, making it a complete studio experience in your browser.

## ✨ Key Features

### 🎧 Pro-Grade Sequencing
- **Dual-Deck Architecture**: Two independent decks with dedicated sequencers, crossfaders, and mixers.
- **Advanced Audio Engine**: Low-latency Web Audio API implementation with high/low-pass filters, delay, and reverb.
- **Dynamic Controls**: Real-time control over pitch, decay, volume, and effects for every track.

### 🤖 AI-Powered Assistant
- **Groq Fast Inference**: Instant generation of professional 16-step patterns (Kick, Bass, Snare, Hi-hat, Sitar).
- **Google Gemini Integration**: AI-generated production tips and Text-to-Speech (TTS) audio analysis with a deep techno-producer vibe.
- **Creative Fallbacks**: Intelligent fallback logic ensures the creative flow never stops, even offline.

### 🌈 Visual Excellence
- **3D Particles**: High-performance Three.js visualizer that pulses to the rhythm of your music.
- **2D Background Canvas**: Dynamic, neon-infused background animations for a premium aesthetic.
- **Premium UI**: Modern, glassmorphic design built for both desktop and mobile performance.

## 🛠️ Technology Stack

- **Frontend**: React 19, TypeScript, Tailwind CSS 4
- **Graphics**: Three.js (WebGL), HTML5 Canvas
- **Audio**: Web Audio API, LameJS
- **AI/ML**: Groq Cloud SDK (LLaMA 3.3), Google Generative AI (Gemini Flash/TTS)
- **Deployment**: Vercel (Serverless Functions)

## 📦 Project Structure

```text
├── src/
│   ├── App.tsx                  # Root application & state management
│   ├── components/              # Modular UI components (Sequencer, Visualizer, etc.)
│   ├── services/                # Core logic (Audio Engine, AI SDKs)
│   ├── utils/                   # Shared helpers & environment config
│   ├── types/                   # Centralized TypeScript definitions
│   └── constants/               # Global configuration & initial states
├── api/                         # Vercel Serverless Functions (Proxy layer)
├── docs/                        # Project documentation & analysis
├── scripts/                     # Utility scripts (Deployment verification)
└── public/                      # Static assets
```

## ⚙️ Local Setup

### Prerequisites
- Node.js (v18+)
- **pnpm** (Recommended for performance and disk space efficiency)

### Installation
1. **Clone the repo:**
   ```bash
   git clone https://github.com/kunalrawal08/techno-music-pad.git
   cd techno-music-pad
   ```

2. **Install dependencies:**
   ```bash
   pnpm install
   ```

3. **Configure API Keys:**
   Create a `.env.local` file in the root directory:
   ```env
   VITE_GROQ_API_KEY=your_groq_api_key_here
   VITE_GEMINI_API_KEY=your_gemini_api_key_here
   ```

4. **Launch development server:**
   ```bash
   pnpm run dev
   ```

## 🚢 Deployment (Vercel)

The project is optimized for **Vercel** deployment:

1. **Push your code** to GitHub.
2. **Connect the repo** to Vercel.
3. **Add Environment Variables** in Vercel Dashboard:
   - `VITE_GROQ_API_KEY`
   - `VITE_GEMINI_API_KEY`
   - `GROQ_API_KEY` (Used by serverless proxy)
4. **Deploy!**

---

<div align="center">
Made with ❤️ for the Techno Community.
</div>
