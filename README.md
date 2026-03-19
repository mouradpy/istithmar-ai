# 🔮 IstithMAR.ai — Smart Investment Guidance for Morocco

> **Morocco's first AI-powered business viability platform** — helping everyday people and small entrepreneurs make smarter, data-driven investment decisions.

[![Made in Morocco](https://img.shields.io/badge/Made%20in-Morocco%20🇲🇦-C9A84C?style=flat-square)](https://github.com/mouradpy)
[![AI Powered](https://img.shields.io/badge/AI-Powered-4A9EFF?style=flat-square)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-MVP%20Live-2ECC89?style=flat-square)](#)

---

## 🌍 What is IstithMAR.ai?

**IstithMAR.ai** (استثمار = "Investment" in Arabic) is an AI-powered web and mobile platform built specifically for the Moroccan market. It acts as a **smart consultant** for anyone who wants to start a small business with a limited budget — eliminating guesswork and reducing failure risk through real local data analysis.

### The Problem It Solves

Thousands of Moroccans invest their life savings into small businesses every year — restaurants, shops, services — without any data to guide them. Most rely on gut feeling or word of mouth. The result? High failure rates, wasted capital, and lost opportunities.

**IstithMAR.ai changes that.**

---

## ✨ Core Features

| Feature | Description |
|---|---|
| 🎯 **Idea Analyzer** | Input your budget, city, neighborhood, and business idea — get a full viability report |
| 📊 **Success Score** | ML-powered percentage prediction based on 5 weighted local factors |
| 📍 **Competitor Mapping** | Visual map of competitor density and optimal zones in your city |
| ⚠️ **Risk Flags** | Auto-detected financial, seasonal, and market risks specific to your location |
| 💡 **Smart Recommendations** | Best neighborhood, optimal price range, and menu/product type suggestions |
| ⚡ **AI Alternatives** | If your idea scores low, the AI suggests better-fit businesses for your budget |
| 🇲🇦 **Moroccan-First Data** | Local demographics, MAD pricing, city-level foot traffic, and social sentiment |

---

## 🚀 Push to GitHub from Windows — Step by Step

### ✅ Step 1 — Install Git for Windows
Download and install from: **https://git-scm.com/download/win**  
During install, choose **"Git from the command line"** when asked.

---

### ✅ Step 2 — Create the repo on GitHub
1. Go to **https://github.com/mouradpy**
2. Click the **"+"** icon → **New repository**
3. Name it: `istithmar-ai`
4. Set it to **Public**
5. Do **NOT** check "Initialize with README" (you already have one)
6. Click **Create repository**

---

### ✅ Step 3 — Set up your project folder on Windows

Open **Command Prompt** (`Win + R` → type `cmd` → Enter) and run:

```bash
cd Desktop
mkdir istithmar-ai
cd istithmar-ai
```

Then copy your two files into this folder:
- `istithmar_ai_with_footer.html`
- `README.md`

---

### ✅ Step 4 — Configure Git (first time only)

```bash
git config --global user.name "Mourad Zerbane"
git config --global user.email "your@email.com"
```

> Replace `your@email.com` with the email linked to your GitHub account.

---

### ✅ Step 5 — Initialize and push

Run these commands one by one:

```bash
git init
git add .
git commit -m "🚀 Initial commit — IstithMAR.ai MVP"
git branch -M main
git remote add origin https://github.com/mouradpy/istithmar-ai.git
git push -u origin main
```

GitHub will ask for your **username** and a **Personal Access Token** (not your password).

> **To get your token:** GitHub → Settings → Developer Settings → Personal Access Tokens → Tokens (classic) → Generate new token → check `repo` scope → copy it and paste it as your password.

---

### 🔄 Every future update — just run:

```bash
cd Desktop\istithmar-ai
git add .
git commit -m "Describe your change here"
git push
```

---

## 🧠 How the AI Analysis Works

```
User Input
  └── Budget (MAD) + City + Neighborhood + Business Idea
        │
        ▼
  Data Collection Layer
  ├── Google Reviews & ratings scraping
  ├── Social media sentiment (Instagram, Facebook, TikTok)
  ├── Competitor density mapping (Google Places API)
  ├── Population & income demographics (HCP data)
  ├── Foot traffic patterns (mobile data signals)
  └── Local pricing trends
        │
        ▼
  ML Viability Engine
  ├── Market Demand Score
  ├── Competition Density Score
  ├── Budget Fit Score
  ├── Location Attractiveness Score
  └── Sentiment Score
        │
        ▼
  Output
  ├── Overall Success % (0–100)
  ├── Risk breakdown
  ├── Actionable recommendations
  └── AI-generated alternative ideas (ranked by predicted success)
```

---

## 🗂️ Project Structure

```
istithmar-ai/
│
├── istithmar_ai_with_footer.html   # Main platform UI (single-file app)
├── README.md                        # You are here
│
├── assets/                          # (coming soon)
│   ├── logo.svg
│   └── screenshots/
│
├── api/                             # (coming soon)
│   ├── analyze.js                   # Core ML analysis endpoint
│   ├── scraper.js                   # Local data collection
│   └── scoring.js                   # Viability scoring engine
│
└── mobile/                          # (coming soon)
    └── app/                         # React Native mobile app
```

---

## 🛠️ Tech Stack

**Current (MVP)**
- Pure HTML5 / CSS3 / Vanilla JavaScript
- Single-file, zero-dependency frontend
- Fully responsive (mobile + desktop)

**Planned (Full Platform)**
- **Frontend:** React.js + Tailwind CSS
- **Mobile:** React Native (iOS & Android)
- **Backend:** Node.js / Express
- **AI/ML:** Python (scikit-learn, TensorFlow) + Claude API (Anthropic)
- **Data Sources:** Google Places API, Meta Graph API, OpenStreetMap
- **Database:** PostgreSQL + Redis (caching)
- **Hosting:** Vercel (frontend) + Railway (backend)

---

## 🗺️ Roadmap

- [x] MVP UI — Analyzer, Results, Recommendations, Alternatives
- [x] Co-founder signature & footer
- [ ] Connect live Claude API for dynamic analysis
- [ ] Integrate Google Places API for real competitor data
- [ ] City coverage: Casablanca, Rabat, Marrakech, Fès, Béni Mellal, Agadir
- [ ] Arabic + French + Darija language support
- [ ] User accounts & saved analyses
- [ ] React Native mobile app
- [ ] B2B API for banks & microfinance institutions

---

## 🤝 Contributing

Contributions, ideas, and feedback are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Founder

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/mouradpy">
        <strong>Mourad Zerbane</strong><br/>
        Co-Founder, IstithMAR.ai<br/>
        🇲🇦 Morocco<br/><br/>
        <img src="https://img.shields.io/badge/GitHub-mouradpy-181717?style=flat-square&logo=github" />
      </a>
    </td>
  </tr>
</table>

---

<p align="center">
  Built with ❤️ for Morocco — empowering small entrepreneurs, one smart investment at a time.<br/>
  <strong>IstithMAR.ai</strong> · استثمار بذكاء<br/><br/>
  <a href="https://github.com/mouradpy">github.com/mouradpy</a>
</p>
