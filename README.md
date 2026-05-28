# Folio – EPUB Reader PWA

A lightweight EPUB reader that installs on iPhone and Android like a native app — no App Store required.

## Files
```
epub-pwa/
├── index.html   ← the entire app
├── manifest.json ← makes it installable
├── sw.js         ← offline support
└── README.md
```

## Deploy for free (pick one)

### Option A: Netlify (easiest, drag & drop)
1. Go to https://netlify.com and sign up free
2. Click **"Add new site" → "Deploy manually"**
3. Drag the entire `epub-pwa` folder onto the page
4. Done — you get a URL like `https://yourapp.netlify.app`

### Option B: GitHub Pages
1. Create a free GitHub account at https://github.com
2. Click **New repository**, name it `folio-reader`, set to Public
3. Upload all 3 files (`index.html`, `manifest.json`, `sw.js`)
4. Go to **Settings → Pages → Source → main branch**
5. Your URL will be `https://yourusername.github.io/folio-reader`

### Option C: Vercel
1. Go to https://vercel.com, sign up free
2. Install Vercel CLI: `npm i -g vercel`
3. In the `epub-pwa` folder run: `vercel`
4. Done — instant URL

---

## Install on iPhone (Safari)
1. Open your deployed URL in **Safari**
2. Tap the **Share button** (box with arrow)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **Add** — the app appears on your home screen like any app

## Install on Android (Chrome)
1. Open your URL in **Chrome**
2. Tap the **three-dot menu**
3. Tap **"Add to Home Screen"** or **"Install app"**
4. Tap **Install**

---

## Features
- Open any `.epub` file from your device
- Table of contents with chapter navigation
- Light / Sepia / Dark themes (saved between sessions)
- Font size adjustment
- Reading position saved automatically
- Works fully offline after first load
- No accounts, no uploads, files stay on your device
