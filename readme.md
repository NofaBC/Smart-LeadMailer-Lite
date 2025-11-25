# Smart LeadMailer Lite™ – Demo

Smart LeadMailer Lite™ is a **Single-File SaaS™ demo** that shows how local lead generation and AI-assisted email outreach could work for small businesses.

It’s built as a **single `index.html` file** (FirstBrick style) for fast demos, live events, and client education.  
All data lives in the browser (no backend, no real email sending).

---

## 🔍 What This Demo Shows

From a business owner’s point of view:

1. **Tell the system who you are**  
   Enter:
   - Business name  
   - Website URL  
   - Niche / industry  
   - Target ZIP code  
   - Gmail address (identity only in the demo)  
   - Short description of your offer

2. **Generate local prospects (demo data)**  
   One click generates a list of **fictional local prospects** in the target ZIP:
   - Name  
   - Company  
   - Email  
   - City / ZIP  
   - Status (New / Email Generated / Sent)

3. **Draft a personalized email in seconds**  
   - Click a prospect  
   - Click **“Generate Email (Demo)”**  
   - The demo auto-fills a warm, conversational email based on:
     - Business info  
     - Niche  
     - Prospect’s name / company / location  

4. **Track activity in a simple dashboard**  
   - Metrics update as you generate and “send” emails:
     - Total prospects  
     - New  
     - Email Generated  
     - Sent  

This is **demo logic only**: nothing is stored on a server and no real emails are sent.

---

## 🧠 Concept & Positioning

Smart LeadMailer Lite™ is designed to:

- Act as a **visual, clickable demo** of an AI-assisted outreach system  
- Open the door to **paid, branded versions** for clients  
- Provide a front-end story that can later be powered by:
  - An **Autonomous AI Agent lead engine** (e.g., `prospector-api`)  
  - Real databases, CRMs, and email APIs

Think of Lite as:

> “Manual ZIP + AI copy + dashboard”  

and Pro as:

> “Autonomous agent + real data + real sending” (future build).

---

## 🧱 Tech Stack

This demo intentionally uses the **simplest possible stack**:

- **HTML / CSS / Vanilla JS** – all in `index.html`
- **No build tools, no backend, no framework**
- **Local state only** (in-memory JavaScript arrays)
- Designed for:
  - Quick deployment on **Vercel**, **GitHub Pages**, **Netlify**, etc.
  - Live demos at networking events, webinars, and sales calls

---

## 🚀 Getting Started

### 1. Run Locally

1. Clone or download the repo.
2. Ensure `index.html` is in the project root.
3. Open `index.html` in your browser:
   - Double-click the file, or  
   - Right-click → “Open With” → your browser.

You should see:

- Business Setup on the left  
- Prospects & Email Composer on the right  
- Prefilled sample data if auto-prefill is enabled

---

### 2. Deploy to Vercel

1. Push this repo to GitHub (for example):

   ```bash
   git init
   git add .
   git commit -m "Smart LeadMailer Lite demo initial commit"
   git branch -M main
   git remote add origin https://github.com/<YOUR-USERNAME>/smart-leadmailer-lite-demo.git
   git push -u origin main
