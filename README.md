# 📰 NewsDigest AI — Instant News Summarizer

>  · AI Graduate Project Challenge

An AI-powered news summarizer that turns any long article into clean, scannable bullet points in seconds. Paste a URL or article text and get an instant digest with TL;DR, tone analysis, and keyword tags.

---

## ✨ Features

- 🔗 **URL or Text mode** — paste a link or raw article text
- 📋 **Bullet point summary** — 3, 5, or 7 key points
- ⚡ **TL;DR** — one-sentence story capture
- 🎨 **Category detection** — Technology, Business, Science, Politics, Sports
- 🎭 **Tone & Bias analysis** — Neutral / Critical / Optimistic + bias check
- ⏱️ **Reading time** estimate
- 🏷️ **Auto-generated tags**
- 📜 **Session history** — last 6 summaries shown as cards
- 🗞️ **Live news ticker** animation

---

## 🚀 Quick Start

```bash
git clone https://github.com/HamidUrRahman-prog/news-summarizer.git
cd news-summarizer
# Open index.html in browser — no server needed!
```

Or deploy to [Netlify Drop](https://news-summarizer-hamid-prog.netlify.app/) in 10 seconds.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, Vanilla JS |
| AI Model | Claude Sonnet (Anthropic API) |
| Fonts | Archivo Black + DM Mono |
| Design | Dark editorial / newspaper aesthetic |

---

## 🧠 How It Works

```
Input (URL or Text)
       ↓
Structured prompt → Claude API
       ↓
JSON response: { title, bullets, tldr, category, tone, bias, tags }
       ↓
Rendered in clean news-magazine UI
```

The prompt instructs Claude to return strict JSON — no markdown, no preamble — making parsing reliable and fast.

---



---

## 🔮 Possible Improvements

- [ ] Fetch real article content via proxy/backend (bypass CORS)
- [ ] Export summary as PDF or shareable card
- [ ] Compare summaries of two articles side by side
- [ ] Add Twitter/X share button per summary
- [ ] Build browser extension version

---

## 👨‍💻 Author



---

## 📄 License

MIT

