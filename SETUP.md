# FitBase 90 — iPhone Setup Guide

## What You're Installing
A Progressive Web App (PWA) that runs like a native iPhone app. It lives on your
home screen, works offline, and stores all your data privately on your phone.
Nothing is sent to any server.

---

## Step 1 — Create a Free GitHub Account
1. Go to github.com
2. Sign up for a free account

---

## Step 2 — Create a New Repository
1. Click the green **"New"** button (top left)
2. Name it: `fitbase` (all lowercase)
3. Set it to **Public**
4. Check **"Add a README file"**
5. Click **"Create repository"**

---

## Step 3 — Upload Your Files
1. In your new repo, click **"Add file" → "Upload files"**
2. Drag and drop these 3 files:
   - `index.html`
   - `manifest.json`
   - `sw.js`
3. Click **"Commit changes"**

---

## Step 4 — Enable GitHub Pages
1. Click **"Settings"** (top of your repo)
2. Click **"Pages"** in the left sidebar
3. Under **"Branch"**, select `main` and click **Save**
4. Wait 1–2 minutes, then your app is live at:
   `https://YOUR-USERNAME.github.io/fitbase/`

---

## Step 5 — Install on Your iPhone
1. Open **Safari** on your iPhone (must be Safari, not Chrome)
2. Go to your URL: `https://YOUR-USERNAME.github.io/fitbase/`
3. Tap the **Share button** (box with arrow at bottom of screen)
4. Scroll down and tap **"Add to Home Screen"**
5. Name it **"FitBase"** and tap **"Add"**

✅ It now appears on your home screen like a real app. Tap it — full screen,
no browser bar, works offline.

---

## Optional: Add a Custom Icon
The app will use a default icon until you add custom ones.
To add an icon:
1. Create two square PNG images: one 192×192px and one 512×512px
2. Name them `icon-192.png` and `icon-512.png`
3. Upload them to your GitHub repo the same way you uploaded the other files
4. Delete the app from your home screen and re-add it from Safari

A simple lime green square with "F" or "90" on it works great.
You can create one free at canva.com.

---

## Your Data
- All workout logs, weight entries, and run history are stored in your
  iPhone's browser storage (localStorage)
- Data persists across app opens
- If you clear Safari's website data, you will lose your logs
- To back up: in the app's Log screen, your history is always visible

---

## Troubleshooting
**App not updating after you changed files?**
Delete from home screen, clear Safari cache, re-add.

**"Add to Home Screen" not appearing?**
Make sure you're using Safari (not Chrome or Firefox).

**App not working offline?**
Open it once with internet, then the service worker caches it for offline use.
