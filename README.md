# CopyForge — AI Ad Copy Generator

> AI-powered platform-specific ad copy generator built with Claude API  
> 🔗 Live App: https://copy-forge.netlify.app/

---

## 📌 Overview

CopyForge is an AI-powered SaaS tool that helps marketers and brands generate compelling, platform-specific ad copy in seconds. Users provide a campaign brief and the app generates tailored copy for Google, Instagram, LinkedIn, Twitter/X, and Facebook — each respecting platform-specific character limits.

Built as part of the **CogCulture Product Management Trainee Assessment**.

---

## 🚀 Features

- **Multi-platform copy generation** — Google Search Ads, Instagram, LinkedIn, Twitter/X, Facebook
- **Platform-aware character limits** — copy is auto-constrained per platform rules
- **Tone selection** — 6 tones including Witty & Bold, Luxury, Urgent, and more
- **One-click copy** — copy all variants to clipboard instantly
- **Powered by Claude AI** — uses Anthropic's `claude-sonnet-4-20250514` model

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| AI Model | Anthropic Claude API (claude-sonnet-4) |
| Deployment | Netlify |
| Fonts | Google Fonts (Syne + DM Sans) |

---

## 📁 Project Structure

```
copyforge-ad-generator/
├── index.html          # Main application (frontend + logic)
├── requirements.txt    # Dependency notes
└── README.md           # Project documentation
```

---

## ⚙️ How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/copyforge-ad-generator.git
   ```

2. Open `index.html` in any browser — no build step needed.

3. Enter your [Anthropic API key](https://console.anthropic.com/settings/keys) in the purple field.

4. Fill in your campaign brief and click **Generate Copy**.

---

## 🔑 API Key Setup

This app uses the Anthropic Claude API directly from the browser.

- Get your API key at [console.anthropic.com](https://console.anthropic.com/settings/keys)
- Paste it into the **API Key field** in the app
- Your key is **never stored** — it only lives in your browser session

---

## 📸 Demo

> 30-second demo video available on request (submitted alongside this repo)

---

## 👤 Built By

Submitted for **CogCulture — Management Trainee (Product Management)** Assessment  
Deadline: May 26, 2026
