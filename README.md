# 🐍 U-Beee Academy

> **Learn • Build • Play** — A cyberpunk-powered CS learning hub built by Ayoub Ajnaki

[![Season](https://img.shields.io/badge/Season-1-00d4ff?style=flat-square&labelColor=0a0f1d)](https://github.com/U-Beee)
[![XP Start](https://img.shields.io/badge/Starting_XP-0-22c55e?style=flat-square&labelColor=0a0f1d)](https://github.com/U-Beee)
[![Status](https://img.shields.io/badge/Status-Live-00d4ff?style=flat-square&labelColor=0a0f1d)](https://github.com/U-Beee)
[![Built by](https://img.shields.io/badge/Built_by-Ayoub_Ajnaki-8b5cf6?style=flat-square&labelColor=0a0f1d)](https://github.com/U-Beee)

---

## 📸 Preview

```
┌─────────────────────────────────────────────────────────┐
│  ██╗   ██╗      ██████╗ ███████╗███████╗███████╗        │
│  ██║   ██║      ██╔══██╗██╔════╝██╔════╝██╔════╝        │
│  ██║   ██║█████╗██████╔╝█████╗  █████╗  █████╗          │
│  ██║   ██║╚════╝██╔══██╗██╔══╝  ██╔══╝  ██╔══╝          │
│  ╚██████╔╝      ██████╔╝███████╗███████╗███████╗        │
│   ╚═════╝       ╚═════╝ ╚══════╝╚══════╝╚══════╝        │
│                                                         │
│         A C A D E M Y                                   │
│         Learn • Build • Play                            │
│                                                         │
│  > Future Software Engineers Start Here_                │
└─────────────────────────────────────────────────────────┘
```

---

## 🚀 What is U-Beee Academy?

U-Beee Academy is a **full-featured, single-file cyberpunk learning platform** built for aspiring software engineers. It combines:

- 📚 **Interactive coding lessons** with real syntax-highlighted examples
- 🎮 **5 browser-playable games** you can actually play right now
- ⚡ **AI-powered coding challenges** evaluated by Claude API
- 🏅 **A real XP & badge system** that saves your progress locally
- 🏆 **A live leaderboard** that updates as you earn XP
- 📝 **A technical blog** with 6 full engineering articles
- 💬 **Discord webhook contact** form

Everything runs from a **single HTML file** — no build step, no dependencies, no server required.

---

## 🗂️ Project Structure

```
ubeee-academy/
│
├── ubeee-academy-fresh.html     ← THE ENTIRE PLATFORM (single file)
│   ├── <style>                  ← Complete CSS design system (~1000 lines)
│   │   ├── CSS Variables        ← Cyberpunk color tokens
│   │   ├── Navigation           ← Fixed glassmorphic navbar
│   │   ├── Hero Section         ← Animated landing with particle canvas
│   │   ├── Learn Hub            ← Track cards + lesson viewer
│   │   ├── Games Arcade         ← All 5 game UIs
│   │   ├── AI Challenges        ← Challenge panel + code editor
│   │   ├── Achievements         ← XP bar + badge grid
│   │   ├── Leaderboard          ← Live rank table
│   │   ├── Projects             ← Portfolio cards with filters
│   │   ├── Roadmap              ← Collapsible phase timeline
│   │   ├── Blog                 ← Article grid + reader view
│   │   ├── About                ← Profile + skill bars
│   │   └── Contact              ← Discord webhook form
│   │
│   ├── <html>                   ← Full page structure (11 sections)
│   │
│   └── <script>                 ← Complete JS engine (~1000 lines)
│       ├── STATE system         ← localStorage persistence
│       ├── XP & leveling        ← 10 levels, 12 badges
│       ├── Canvas background    ← Particle + grid animation
│       ├── Learn Hub engine     ← Track/lesson rendering
│       ├── 5 Game engines       ← Snake, Pong, TTT, Hangman, Typing
│       ├── Challenge engine     ← Claude API integration
│       ├── Leaderboard          ← Live XP-driven rankings
│       ├── Blog engine          ← Article grid + reader
│       └── Contact webhook      ← Discord delivery
│
└── README.md                    ← This file
```

---

## ⚡ Features

### 📚 Learn Hub — 5 Tracks, 17 Lessons

| Track | Lessons | XP Available |
|-------|---------|-------------|
| 🐍 Python Mastery | 5 | 125 XP |
| 🧮 Algorithms & DSA | 3 | 75 XP |
| 🌐 Web Development | 2 | 50 XP |
| 🎮 Game Dev (Unity) | 1 | 25 XP |
| 🤖 AI & Machine Learning | 1 | 25 XP |

Every lesson has:
- Syntax-highlighted code blocks with one-click copy
- Pro Tips from real engineering practice
- Progress tracking saved to localStorage
- XP reward on completion

---

### 🎮 Games Arcade — 5 Playable Games

| Game | Controls | XP Reward |
|------|----------|-----------|
| 🐍 Neon Snake | Arrow Keys / WASD | Score ÷ 10 × 5 XP |
| 🏓 Cyber Pong | W/S · ↑/↓ | +20 XP per match |
| ❌ Tic-Tac-Toe AI | Click | +20 XP per win |
| 🔤 CS Hangman | Keyboard A–Z | +40 XP per solve |
| ⌨️ Typing Test | Keyboard | +15 to +50 XP by WPM |

- Snake: neon glow trail, increasing speed, canvas rendering
- Pong: realistic physics, paddle angle affects ball direction
- Tic-Tac-Toe: 3 modes — Easy AI, **unbeatable Minimax AI**, 2-player
- Hangman: 10 real CS vocabulary words with canvas gallows
- Typing Test: real WPM, accuracy, error tracking, 60s timer

---

### ⚡ AI Challenge Engine — 4 Challenges

| Challenge | Difficulty | XP |
|-----------|------------|-----|
| Two Sum | 🟢 Easy | 50 XP |
| Valid Palindrome | 🟢 Easy | 40 XP |
| Fibonacci — Memoized | 🟡 Medium | 75 XP |
| BST Validator | 🔴 Hard | 120 XP |

- Write code in Python, JavaScript, or Java
- Solutions evaluated live by **Claude claude-sonnet-4-20250514**
- AI gives: verdict, complexity analysis, technical feedback, improvement tip
- AI Hint button gives non-spoiler nudges (counts toward AI Whisperer badge)
- XP awarded only once per challenge

---

### 🏅 XP & Badge System

**10 Level Tiers:**

| Level | Name | XP Required |
|-------|------|------------|
| 1 | Newcomer | 0 XP |
| 2 | Initiate | 100 XP |
| 3 | Coder | 300 XP |
| 4 | Builder | 600 XP |
| 5 | Engineer | 1,000 XP |
| 6 | Architect | 1,500 XP |
| 7 | Specialist | 2,200 XP |
| 8 | Expert | 3,000 XP |
| 9 | Master | 4,000 XP |
| 10 | Elite | 5,500 XP |

**12 Badges to Unlock:**

| Badge | Condition | XP Bonus |
|-------|-----------|---------|
| 📖 First Lesson | Complete 1 lesson | +50 XP |
| 🐍 Pythonista | Complete 3 Python lessons | +100 XP |
| ✅ Problem Solver | Solve 1 challenge | +50 XP |
| ⚡ Triple Threat | Solve 3 challenges | +150 XP |
| 🏆 Challenge Master | Solve all 4 challenges | +300 XP |
| 🎮 Player One | Play 1 game | +30 XP |
| 🕹️ Game Master | Play all 5 games | +200 XP |
| ⌨️ Speedster | Complete Typing Test | +80 XP |
| 🧠 Curious Mind | Open 3 different tracks | +75 XP |
| 🔥 Rising Engineer | Reach Level 5 | +250 XP |
| 🤖 AI Whisperer | Use AI Hint 3 times | +120 XP |
| 🏗️ Architect | Reach 1,000 XP | +500 XP |

> **All badges are locked at start. You earn them yourself.**

---

### 🏆 Leaderboard

The leaderboard shows only **Ayoub** at Season 1 start. As you earn XP through lessons, games, and challenges, your score updates in real time. Every XP action triggers a live leaderboard refresh — you're setting the all-time record for Season 1.

---

## 🛠️ Setup & Deployment

### Option 1: Open Locally (Instant)

```bash
# Just open the file in any modern browser
open ubeee-academy-fresh.html

# Or on Windows
start ubeee-academy-fresh.html
```

> ✅ Works offline. Progress saves to browser localStorage.

---

### Option 2: GitHub Pages (Free Hosting)

```bash
# 1. Create a new GitHub repository called "ubeee-academy"

# 2. Clone it
git clone https://github.com/U-Beee/ubeee-academy.git
cd ubeee-academy

# 3. Add the file (rename for cleaner URL)
cp ubeee-academy-fresh.html index.html

# 4. Push
git add .
git commit -m "🚀 Launch U-Beee Academy Season 1"
git push origin main

# 5. Enable GitHub Pages:
#    Repo Settings → Pages → Branch: main → / (root) → Save

# Your site will be live at:
# https://u-beee.github.io/ubeee-academy/
```

---

### Option 3: Vercel (Fastest)

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
cp ubeee-academy-fresh.html index.html
vercel --prod

# Done in ~30 seconds. Get a live URL instantly.
```

---

### Option 4: Netlify Drag & Drop

1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Rename the file to `index.html`
3. Drag the file into the browser
4. Get a live URL in seconds — no account needed

---

## 🔧 Configuration

### Discord Webhook (Contact Form)

To receive contact messages directly in your Discord server:

1. Open your Discord server → Server Settings → Integrations → Webhooks → New Webhook
2. Copy the webhook URL
3. Open `ubeee-academy-fresh.html` in a text editor
4. Find this line (near the bottom of the `<script>` section):

```javascript
const webhookUrl = 'https://discord.com/api/webhooks/YOUR_WEBHOOK_ID/YOUR_WEBHOOK_TOKEN';
```

5. Replace with your real webhook URL:

```javascript
const webhookUrl = 'https://discord.com/api/webhooks/1234567890/abcdefghijk...';
```

6. Save and redeploy.

---

### AI Challenge Engine (Claude API)

The challenge evaluator calls the Anthropic API directly from the browser. For production use, route calls through a backend proxy:

**Direct (development only):**
```javascript
// Already configured in the HTML — works as-is for local testing
// Note: exposes API key in browser — use proxy for production
```

**Via backend proxy (recommended for public deployment):**
```javascript
// Replace the fetch URL in runCh() and getHint():
const res = await fetch('/api/evaluate', {
  method: 'POST',
  headers: { 'Content-Type': 'application/json' },
  body: JSON.stringify({ code, lang, challenge: c.name, difficulty: c.diff })
});
```

**Minimal Express proxy:**
```javascript
// server.js
import express from 'express';
import Anthropic from '@anthropic-ai/sdk';

const app = express();
const client = new Anthropic(); // reads ANTHROPIC_API_KEY from env

app.use(express.json());

app.post('/api/evaluate', async (req, res) => {
  const { code, lang, challenge } = req.body;
  const msg = await client.messages.create({
    model: 'claude-sonnet-4-20250514',
    max_tokens: 300,
    messages: [{ role: 'user', content: buildPrompt(code, lang, challenge) }]
  });
  res.json({ text: msg.content[0].text });
});

app.listen(3000);
```

---

## 📊 XP Earning Reference

| Action | XP |
|--------|----|
| Open a new game for the first time | +15 XP |
| Complete any lesson | +25 XP |
| Win at Tic-Tac-Toe | +20 XP |
| Complete a Pong match | +20 XP |
| Solve Hangman | +40 XP |
| Typing Test — under 40 WPM | +15 XP |
| Typing Test — 40–60 WPM | +25 XP |
| Typing Test — 60–80 WPM | +35 XP |
| Typing Test — 80+ WPM | +50 XP |
| Snake game score 10+ | +5 XP per 10 pts |
| Solve "Two Sum" | +50 XP |
| Solve "Valid Palindrome" | +40 XP |
| Solve "Fibonacci" | +75 XP |
| Solve "BST Validator" | +120 XP |
| Unlock a badge | +30 to +500 XP (bonus) |

---

## 🗺️ Career Roadmap

The platform includes a 5-phase interactive career roadmap:

```
Phase 01 — The Foundation
  HTML · CSS · Python · Git · Linux CLI
  └── Projects: Portfolio, CLI Calculator, Weather Script

Phase 02 — The Builder
  JavaScript · React · Node.js · REST · SQL
  └── Projects: Snake, Pong, TTT, U-Beee Backend

Phase 03 — The Architect
  System Design · WebSockets · Redis · Docker
  └── Projects: Live Leaderboard, Auth System, Redis Cache

Phase 04 — The Specialist
  AI/ML · Unity · WebGL · Advanced DSA
  └── Projects: AI Mentor Bot, 3D Game Prototype

Phase 05 — The Professional
  Open Source · Interviews · Launch · Career
  └── Projects: ubeee.dev, OS Library, Tech Talk, First Job
```

---

## 📝 Blog Articles

| Title | Category | Read Time |
|-------|----------|-----------|
| How I Mastered Decorators | Python | 8 min |
| Sliding Window Pattern | Algorithms | 11 min |
| Real-Time Leaderboard with Redis | Web Dev | 14 min |
| Unity vs Unreal Engine 2025 | Game Dev | 9 min |
| Neural Network from Scratch | AI & ML | 18 min |
| JWT vs Sessions | Security | 7 min |

---

## 🔗 Contact & Social

| Platform | Link |
|----------|------|
| 📧 Email | [Ajnakiayoub@gmail.com](mailto:Ajnakiayoub@gmail.com) |
| 🐙 GitHub | [github.com/U-Beee](https://github.com/U-Beee) |
| 🎮 Discord | u_beee |
| 📱 Phone/WeChat | +86 186 7916 9402 |
| 📍 Location | Nanchang City, Jiangxi, China |

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3 (Custom Properties, Grid, Flexbox, Glassmorphism) |
| Fonts | JetBrains Mono, Orbitron, Inter (Google Fonts) |
| Animation | CSS Keyframes, Canvas API, requestAnimationFrame |
| Games | HTML5 Canvas API (vanilla JS) |
| AI Evaluation | Anthropic Claude claude-sonnet-4-20250514 |
| State | localStorage (auto-save on every XP action) |
| Deployment | Any static host (GitHub Pages, Vercel, Netlify) |
| Backend (optional) | Node.js + Express (for API proxy) |

---

## 📦 Full Stack Version (Future)

For the full production architecture documented in this project:

```
Frontend:  React 18 + TypeScript + Vite + Tailwind CSS + GSAP
Backend:   Node.js + Express + TypeScript + Socket.io
Database:  PostgreSQL 16 + Prisma ORM
Cache:     Redis 7 (Sorted Sets for leaderboard, Hash for users)
Auth:      JWT + bcrypt + HTTP-only cookies + RBAC
CI/CD:     Docker + GitHub Actions → Vercel + Railway
AI:        Anthropic Claude API (claude-sonnet-4-20250514)
```

---

## 🔒 Privacy & Data

- **No server.** All data stays in your browser's `localStorage`.
- **No tracking.** No analytics, no cookies, no external calls except Google Fonts and the Anthropic API (challenge evaluation only).
- **No accounts.** Your progress is tied to the device and browser you use.
- To reset progress: open browser DevTools → Application → localStorage → delete `ubeee_state`.

---

## 📄 License

```
MIT License

Copyright (c) 2025 Ayoub Ajnaki — U-Beee Academy

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software to use, copy, modify, merge, and distribute
it freely, subject to the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
```

---

## 🚀 Quick Start

```bash
# 1. Download ubeee-academy-fresh.html
# 2. Open in browser
# 3. Click "Start Learning"
# 4. Earn your first XP
# 5. The rest is up to you, Ayoub. 🎯
```

---

<div align="center">

**Built with 💙 by Ayoub Ajnaki**

*"Future Software Engineers Start Here"*

[GitHub](https://github.com/U-Beee) · [Email](mailto:Ajnakiayoub@gmail.com) · Discord: u_beee

</div>
