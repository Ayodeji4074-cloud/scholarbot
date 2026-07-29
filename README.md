# ScholarBot 📚
**AI-Powered Academic Research Assistant**
*LD7237 Hackathon — MSc Big Data & Data Science Technologies, University of East London*

---

## What it does
ScholarBot uses a two-agent AI pipeline (built on Flowise + Gemini) to turn any research topic into:
- ✅ Genuine, verified academic paper references
- ✅ Research gaps and originality opportunities  
- ✅ 4–5 unique research angle ideas
- ✅ A full, detailed literature review (600+ words)
- ✅ A step-by-step execution roadmap
- ✅ Downloadable PDF report with citation formatting

## Tech Stack
| Layer | Tool |
|---|---|
| AI Agent Pipeline | Flowise Cloud (multi-agent) |
| LLM | Google Gemini 2.5 Flash |
| Frontend | HTML + CSS + Vanilla JavaScript |
| PDF Export | jsPDF (CDN) |
| Deployment | Vercel |

## Setup

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/scholarbot.git
cd scholarbot
```

### 2. Add your Flowise API endpoint
Open `index.html` and replace line:
```javascript
const FLOWISE_API_URL = 'YOUR_FLOWISE_API_ENDPOINT_HERE';
```
with your actual Flowise endpoint URL from the `</>` icon in your Flowise flow.

### 3. Deploy to Vercel
- Push to GitHub
- Go to vercel.com → Import project → Select this repo
- Deploy (no build settings needed — it's a static site)

## Project Structure
```
scholarbot/
├── index.html     ← entire frontend (HTML + CSS + JS)
├── vercel.json    ← Vercel deployment config
└── README.md      ← this file
```

## Team
Built by MSc Big Data & Data Science students at University of East London.

---
*ScholarBot is an academic tool. Always verify AI-generated paper references independently.*