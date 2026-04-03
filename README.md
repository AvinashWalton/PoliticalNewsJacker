# 🗞️ PoliticalNewsJacker

> **जन-सवाल, सरकारी जवाब** — Fetch political news. Ask smarter questions. Hold power accountable.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen?style=for-the-badge&logo=github)](https://avinashwalton.github.io/PoliticalNewsJacker)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](./LICENSE)
[![Made in India](https://img.shields.io/badge/Made%20with%20%E2%9D%A4-India-orange?style=for-the-badge)](https://github.com/avinashwalton)
[![No Backend](https://img.shields.io/badge/No%20Backend-Static%20Site-blue?style=for-the-badge&logo=html5)](https://avinashwalton.github.io/PoliticalNewsJacker)

---

## ✨ What is PoliticalNewsJacker?

**PoliticalNewsJacker** is a free, AI-powered micro-SaaS tool that helps citizens, journalists, students, and political activists:

1. 📡 **Fetch live political news** — Bihar, India, and World (80% Hindi, 20% English)
2. 🧠 **Summarize issues** using Google Gemini AI — in 3 structured Hindi bullet points
3. ✍️ **Auto-generate professional government questions** — data-driven, non-partisan, logical
4. 🐦 **Post directly to X (Twitter)** with one click using Twitter Web Intents
5. 📋 **Save drafts locally** to your browser — no login, no database

Inspired by the intellectual political communication style of leaders like **Raghav Chadha** — asking the right questions, the right way.

---

## 🖥️ Live Preview

![PoliticalNewsJacker Screenshot](https://via.placeholder.com/1280x720/0f0f18/e8452a?text=PoliticalNewsJacker+Screenshot)

---

## 🚀 Features

| Feature | Description |
|---|---|
| 📰 Live News Feed | Fetches real-time political headlines via GNews API |
| 📍 Smart Filters | Filter by **Bihar**, **India**, or **World** news |
| 🤖 AI Summary | 3-bullet Hindi summary: समस्या, विवाद, जनता पर असर |
| ✍️ Question Drafter | Gemini AI writes a non-partisan, professional government question |
| 🎭 Tone Selector | Choose: **Data-Driven**, **Emotional Appeal**, or **Direct Question** |
| 🐦 One-Click Tweet | Opens X/Twitter pre-filled with your drafted question |
| 📋 Draft History | Save, view, and manage all drafts in `localStorage` |
| 🔐 BYOK Model | Bring Your Own Key — API keys stay in your browser only |
| 📱 Responsive | Mobile-first, works on all screen sizes |
| 🌙 Dark Theme | Elegant dark editorial design |

---

## 🛠️ Tech Stack

- **HTML5** — Semantic structure
- **Tailwind CSS** (via CDN) — Utility-first styling
- **Vanilla JavaScript** — Zero dependencies, no frameworks
- **Google Gemini API** — `gemini-1.5-flash` for AI summarization & question drafting
- **GNews API** — Free tier for real-time news headlines
- **Twitter Web Intents** — Native tweet sharing
- **localStorage** — Client-side persistence for keys & drafts

> **100% Static** — Deployable anywhere: GitHub Pages, Netlify, Vercel, or just open the file locally!

---

## ⚙️ Setup & Installation

### Step 1: Get Your Free API Keys

**GNews API** (for news fetching):
1. Go to [gnews.io](https://gnews.io)
2. Sign up for a free account
3. Copy your API key from the dashboard
4. Free tier: **100 requests/day**

**Google Gemini API** (for AI features):
1. Go to [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Click **"Create API Key"**
3. Copy the key starting with `AIzaSy...`
4. Free tier: **Generous daily quota**

### Step 2: Deploy or Run Locally

**Option A — GitHub Pages (Recommended):**
```bash
# Fork this repo, then enable GitHub Pages in Settings → Pages → Deploy from main branch
```

**Option B — Run Locally:**
```bash
git clone https://github.com/avinashwalton/PoliticalNewsJacker.git
cd PoliticalNewsJacker
# Just open index.html in any browser — no server needed!
open index.html
```

**Option C — Quick CDN:**
```html
<!-- Just download index.html and open it directly in your browser -->
```

### Step 3: Add Your API Keys

1. Open the app in your browser
2. Click the **⚙️ Settings** button (top right)
3. Enter your **GNews API key** and **Gemini API key**
4. Select preferred language (Hindi / English / Both)
5. Click **Save Settings**

Your keys are stored in `localStorage` and **never leave your browser**.

---

## 📖 How to Use

```
1. Select a region filter → Bihar / India / World
2. Click any headline in the Left News Feed
3. Right Panel populates with article details
4. Click "समस्या पढ़ें" → AI generates 3-bullet Hindi summary
5. Select a Tone → Data-Driven / Emotional / Direct
6. Click "सवाल लिखें" → AI drafts a professional government question
7. Click "Post to X (Twitter)" → Opens Twitter pre-filled
8. Click "Save Draft" → Saves to My Drafts tab
```

---

## 🎯 AI Prompting Philosophy

The AI is instructed to:
- ✅ Be **non-partisan** — never target political parties
- ✅ Focus on **Jan Samasya** (public issues) only
- ✅ Never name or attack individual politicians
- ✅ Use **facts and data** wherever possible
- ✅ Communicate in **Hindi/Hinglish** for maximum reach
- ✅ Keep tone: **Educated · Intellectual · Polite but Firm**

---

## 📁 Project Structure

```
PoliticalNewsJacker/
├── index.html          # Complete app — all HTML, CSS, JS in one file
├── README.md           # This file
└── LICENSE             # MIT License
```

---

## 🔒 Privacy & Security

- **No backend server** — completely static
- **No data collection** — zero analytics, zero tracking
- **API keys stay local** — stored only in your browser's `localStorage`
- **No third-party scripts** except Tailwind CSS CDN and Google Fonts
- You can self-host and modify freely under MIT License

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repo
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

**Ideas for contribution:**
- [ ] RSS feed support as fallback news source
- [ ] Support for more Indian regional languages (Tamil, Telugu, Bengali)
- [ ] WhatsApp share button
- [ ] Export drafts as PDF
- [ ] Dark/Light theme toggle
- [ ] Keyword trend graph

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](./LICENSE) for more information.

---

## 👤 Author

**Avinash Walton**

- GitHub: [@avinashwalton](https://github.com/avinashwalton)
- Twitter/X: [@avinashwalton](https://twitter.com/avinashwalton)

---

<p align="center">
  Made with ❤️ in India by <strong>Avinash Walton</strong>
</p>

<p align="center">
  <em>जन-सवाल, सरकारी जवाब — Ask smarter. Demand better.</em>
</p>
