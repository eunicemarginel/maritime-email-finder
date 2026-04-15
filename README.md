# Maritime Email Finder 🚢

A free browser-based tool to find contact emails for maritime agents and shipping companies in Singapore.

Built for the Singapore maritime industry — port agents, ship managers, brokers, and freight forwarders.

---

## Features

- 🔍 **Single search** — find emails for one company instantly
- 📋 **Bulk search** — paste a list of companies, process them all
- 🧠 **Pattern guessing** — generates common email patterns (info@, ops@, chartering@) when no direct email is found
- ✅ **Email verification** — checks emails via Hunter.io SMTP verification
- 📤 **CSV export** — download results for use in your CRM or outreach tool
- 🆓 **Demo mode** — works without API keys using simulated data so you can test it immediately

---

## Live Demo

Hosted on Vercel → *(add your URL here after deployment)*

---

## Setup

This is a pure static HTML app — no build step, no npm install, no dependencies.

Just open `index.html` in any browser.

### Optional: Enable Live Results

To switch from Demo Mode to real live results, get these free API keys:

| Key | Where to get it | Free tier |
|-----|----------------|-----------|
| Hunter.io API Key | [hunter.io/api](https://hunter.io/api) | 25 searches/month |
| Google Custom Search API Key | [Google Cloud Console](https://console.cloud.google.com) | 100 searches/day |
| Google Search Engine ID (cx) | [Google Programmable Search](https://programmablesearchengine.google.com) | Free |

Enter them in the **API Keys** panel inside the app. Keys are stored only in your browser session — never sent anywhere except the official APIs.

---

## Deployment

### Vercel (recommended)

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → New Project → Import from GitHub
3. Select this repo — Vercel auto-detects the static config
4. Click Deploy — done ✅

### Manual

Just drag `index.html` to [Netlify Drop](https://app.netlify.com/drop) for an instant public URL.

---

## Tech Stack

- Vanilla HTML + CSS + JavaScript (zero dependencies)
- [Hunter.io API](https://hunter.io/api-documentation) — email discovery & verification
- [Google Custom Search API](https://developers.google.com/custom-search/v1/overview) — domain lookup

---

## Suggested Maritime Directories to Source Company Names

- [MPA Singapore Maritime Singapore Directory](https://www.mpa.gov.sg)
- [Kompass Singapore](https://sg.kompass.com)
- [Singapore Yellow Pages — Marine](https://www.yellowpages.com.sg)

---

## License

MIT — free to use, modify, and distribute.

---

*Built for Singapore maritime industry professionals.*
