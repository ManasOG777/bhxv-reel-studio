# REEL STUDIO — Viral Content OS India 🇮🇳

A production-grade creator tool for Indian Gen Z content creators targeting Instagram Reels and YouTube Shorts.

## Features

- 🔥 **Viral Trends** — 9 trending formats with heat scores
- 🇮🇳 **Hinglish Live** — Auto-refreshing trending phrases for India
- ✍️ **Caption Generator** — Full caption + hashtags + SEO keywords
- ⏰ **Best Time Tool** — Niche-specific upload heatmap for India
- 📡 **Reach Maximiser** — Niche-specific growth playbooks
- 🪝 **Hook Builder** — Hinglish hooks with live phone mockup preview
- 🤖 **Script Generator** — Full reel scripts with shot lists
- 📊 **Virality Scorer** — Pre-publish reel audit
- 📈 **Algorithm Map** — 2026 Instagram + TikTok signal ranking
- 🎵 **Trending Audio** — Sounds to jump on now
- 🧰 **Creator Toolkit** — Checklist, length guide, quick tools

## Deploy to Vercel

### Option 1: Vercel CLI
```bash
npm install -g vercel
cd reel-studio
vercel
```

### Option 2: Vercel Dashboard
1. Go to [vercel.com](https://vercel.com)
2. Click "Add New Project"
3. Upload this folder or connect your GitHub repo
4. Framework: **Other / Static**
5. Click Deploy — done in 30 seconds ✅

### Option 3: GitHub + Vercel (recommended)
1. Push this folder to a GitHub repo
2. Import the repo on Vercel
3. Auto-deploys on every push

## Project Structure

```
reel-studio/
├── index.html      # Complete single-file app
├── vercel.json     # Vercel routing config
└── README.md       # This file
```

## Tech Stack

- Pure HTML + CSS + Vanilla JS (zero dependencies)
- Google Fonts: Bebas Neue, DM Sans, DM Mono
- Optimised for Android, iOS, macOS, Windows
- PWA-ready (mobile web app capable)

## Performance

- First paint < 1 second
- Zero JS frameworks = zero bundle weight
- All data client-side = zero backend needed
- CDN-served fonts with preconnect

## Customisation

All content data is at the top of `index.html` in the `// ── DATA ──` section:

- `HINGLISH_TRENDS` — Trending Hinglish phrases
- `AUDIO_TRENDS` — Trending audio recommendations
- `TIMING_DATA` — Hour-by-hour engagement data per niche
- `REACH_DATA` — Niche-specific growth tactics
- `SCRIPT_DB` — Script templates per niche + format
- `CAPTION_DB` — Caption templates per niche + tone

Built for Indian creators 🇮🇳 | 2026
