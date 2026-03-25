# Ryutaro Kanno

**Full-stack developer building AI-powered products.**

I ship fast — 5 deployed products in 4 months, all built with AI-assisted development (Claude Code).

## What I Build

### [FormCheck AI](https://formcheck-ai.vercel.app) — Real-time exercise form checker
AI-powered pose estimation that runs **entirely in the browser** — $0 server cost.
- **Stack**: Next.js 16, TypeScript, MediaPipe Pose, Tailwind CSS
- **Features**: Real-time skeleton overlay, rep counting, form scoring, voice feedback
- **Architecture**: One Euro Filter smoothing, hysteresis FSM, body-normalized scoring

### [Dance Mirror](https://dance-mirror-chi.vercel.app) — TikTok dance practice app
Learn dances by comparing your poses against reference choreography in real-time.
- **Stack**: Next.js 16, MediaPipe, DTW (Dynamic Time Warping), Zustand, Dexie (IndexedDB)
- **Key tech**: Hybrid scoring (60% joint angles + 40% cosine similarity), body normalization (hip-centered + shoulder-width scaling)

### Claude Mobile — Claude Code web UI for iPhone
Custom web interface to run Claude Code from mobile via Tailscale VPN.
- **Stack**: Python aiohttp, WebSocket, PTY, xterm.js, LINE Bot
- **Why**: Built my own dev environment so I can code from anywhere

### Multi-Agent Prediction System
8-agent parallel analysis architecture for sports prediction with cross-validation.
- **Stack**: Python, LightGBM, Claude Code orchestration
- **Scale**: 1,717-race backtest, v2.2 scoring system with 12 iterative improvements
- **Design**: Each agent has a specialized role; parent agent performs contradiction checking

## Tech Stack

**Frontend**: Next.js 16 / React 19 / TypeScript / Tailwind CSS v4 / Zustand

**AI/ML**: MediaPipe / LightGBM / Pose Estimation / DTW

**Backend**: Python / Node.js / WebSocket / PTY / GAS

**Infrastructure**: Vercel / Tailscale / WSL2 / Git

**AI Dev Tools**: Claude Code (1,800+ sessions worth of experience)

## Stats

- Shipped 5 products to production in 4 months
- 48 freelance projects delivered
- 1.8B+ tokens processed through Claude Code

## Links

- [FormCheck AI](https://formcheck-ai.vercel.app) — try it now, no signup needed
- [Dance Mirror](https://dance-mirror-chi.vercel.app) — practice dances in your browser
