[README.md](https://github.com/user-attachments/files/28200560/README.md)
# Morning Market Briefing App

A sleek, terminal-aesthetic pre-market briefing tool for day and swing options traders.

## What it does
- Stores your watchlist and open trades in your browser (persists between sessions)
- Generates a fully structured briefing prompt tailored to your positions
- One click to copy + open Claude, where live search runs your full intel report

## How to deploy (free, takes 5 minutes)

### Option A — GitHub Pages (recommended, permanent free URL)

1. Go to https://github.com and create a free account if you don't have one
2. Click the "+" icon → "New repository"
3. Name it: `morning-briefing` — set to **Public** — click "Create repository"
4. Click "uploading an existing file" on the next page
5. Drag and drop `index.html` from this folder
6. Click "Commit changes"
7. Go to Settings → Pages → Source: select "main" branch → Save
8. Your app is live at: `https://YOUR-USERNAME.github.io/morning-briefing`

### Option B — Netlify Drop (even faster, no account needed)

1. Go to https://app.netlify.com/drop
2. Drag the entire `morning-briefing-app` folder onto the page
3. Get an instant URL like `https://random-name-123.netlify.app`
4. Optionally sign up to claim a custom name

### Option C — Vercel (also free)

1. Go to https://vercel.com and sign up with GitHub
2. Click "Add New Project" → "Import" your GitHub repo (after Option A above)
3. Deploy in one click — get a URL like `https://morning-briefing.vercel.app`

## Add to phone home screen

### iPhone
1. Open the URL in Safari
2. Tap the Share button (box with arrow)
3. Tap "Add to Home Screen"
4. Name it "Briefing" → Add

### Android
1. Open the URL in Chrome
2. Tap the three-dot menu
3. Tap "Add to Home screen"

## Features
- Dark trading terminal aesthetic
- Live market open/closed status
- Watchlist + Open Trades (two separate sections)
- Tickers persist in browser localStorage — no login needed
- Generates a full structured prompt for Claude with web search
- One-button copy + direct link to Claude
