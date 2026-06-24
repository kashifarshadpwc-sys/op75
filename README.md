# Operation 75 — install as an iPhone app

This folder turns your training dashboard into an installable app on your iPhone 17 Pro Max. No App Store, no fees, no developer account. About 10 minutes total.

You'll end up with an icon on your home screen labeled "Op 75" that opens full-screen, works offline once loaded, and saves your data locally on your phone.

---

## What's in this folder

- `index.html` — the main app (renamed from operation-75.html)
- `manifest.json` — tells iOS how to install it as an app
- `sw.js` — service worker, enables offline use
- `icon-180.png`, `icon-192.png`, `icon-512.png`, `icon-1024.png` — app icons

All 7 files need to go up together.

---

## Step 1 · Create a GitHub account (skip if you already have one)

1. Open Safari on your phone or browser on laptop, go to **github.com**.
2. Click **Sign up**. Pick a username — this becomes part of your URL, so keep it clean (e.g., `kasharshad`, `kashif-arshad`).
3. Verify your email. Free tier is all you need.

---

## Step 2 · Create a new repository

1. After signing in, click the **+** in the top-right → **New repository**.
2. Repository name: `op75` (lowercase, no spaces)
3. Description: optional, "My training camp"
4. Set it to **Public** (required for free GitHub Pages).
5. **Do NOT** check "Add a README" — leave the repo empty for now.
6. Click **Create repository**.

You'll land on a page that says "Quick setup" with some commands. Ignore those — we'll upload via the web UI.

---

## Step 3 · Upload these files

1. On the repo page, click **uploading an existing file** (it's a link in the gray box), or go to `https://github.com/YOUR-USERNAME/op75/upload/main`
2. **Drag all 7 files from this folder into the upload box** (index.html, manifest.json, sw.js, and the 4 icon PNGs).
3. Scroll down, leave the commit message as default ("Add files via upload").
4. Click **Commit changes**.

The files should now appear in your repo.

---

## Step 4 · Turn on GitHub Pages

1. In your repo, click **Settings** (top right of the repo navigation).
2. In the left sidebar, click **Pages**.
3. Under "Build and deployment" → **Source**: select **Deploy from a branch**.
4. **Branch**: select **main** and **/ (root)**. Click **Save**.
5. Wait 30–60 seconds. Refresh the page.
6. You'll see a green box: *"Your site is live at `https://YOUR-USERNAME.github.io/op75/`"*

Copy that URL.

---

## Step 5 · Install on your iPhone home screen

1. On your iPhone 17 Pro Max, open **Safari** (this only works in Safari, not Chrome).
2. Paste your URL: `https://YOUR-USERNAME.github.io/op75/`
3. Wait for the app to fully load.
4. Tap the **Share** icon (square with arrow pointing up) at the bottom of Safari.
5. Scroll down in the share sheet → tap **Add to Home Screen**.
6. Edit the name if you want (default: "Op 75"). Tap **Add**.

The "Op 75" icon now lives on your home screen.

---

## What works now

- Tap the icon → opens **full-screen**, no Safari bars
- All your **food log, workout log, weight log, checklists** save on your phone
- Works **offline** once loaded (gym Wi-Fi optional)
- Looks and feels like a real app

---

## What to know

- **Data is stored locally on your phone** — not on GitHub. If you delete the app, your logged data is gone. Back up by exporting your browser data periodically if it matters.
- **To update the app later**: I'll send you a new `index.html`, you replace the old one in GitHub, and your home-screen app auto-updates the next time you open it with internet.
- **Your sister wants it too?** Send her the URL. She taps "Add to Home Screen" too. Her data stays separate on her phone.

---

## If something doesn't work

- **The share sheet doesn't show "Add to Home Screen"**: You're not in Safari. Open the URL in Safari specifically.
- **The icon shows up generic, not the OP 75 design**: Wait 30 sec after upload for GitHub Pages to deploy, then re-add to home screen.
- **The page is blank**: Wait 2–3 minutes after enabling GitHub Pages — first deploy can take a moment. Try the URL in a private browser tab to confirm.
- **Tracker doesn't save data**: Make sure you opened it from the home-screen icon (not Safari) — Safari and the installed app can have separate storage on iOS.

---

Built 24 June 2026 · Kashif Arshad · Operation 75
