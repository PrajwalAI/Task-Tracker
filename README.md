# Route CH — Switzerland Tracker (PWA)

A daily/weekly/monthly/yearly tracker for your Data Analyst → MSc Switzerland plan.
Installable as an app icon on your phone. Data is saved locally on your device (`localStorage`) — private to you, no account or server needed.

## Fastest way to get this on your phone: GitHub Pages (free, ~5 minutes)

1. Go to https://github.com and create a free account if you don't have one.
2. Click **New repository**. Name it e.g. `route-ch-tracker`. Set it to **Public** (required for free Pages). Click **Create repository**.
3. On the new repo page, click **uploading an existing file** (or "Add file" → "Upload files").
4. Drag in all 5 files from this folder: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`. Commit.
5. Go to **Settings** → **Pages** (left sidebar).
6. Under "Build and deployment", set **Source** to "Deploy from a branch", branch = `main`, folder = `/ (root)`. Save.
7. Wait ~1 minute, then your app is live at:
   `https://YOUR-USERNAME.github.io/route-ch-tracker/`

## Install it as an app on your phone

**iPhone (Safari):** open the link above → tap the Share icon → **Add to Home Screen**.
**Android (Chrome):** open the link → tap the ⋮ menu → **Add to Home screen** / **Install app**.

It'll open full-screen with its own icon, no browser bar — feels like a native app.

## Notes

- **Data lives on this one device.** If you install it on both your phone and laptop, they will NOT sync with each other (each keeps its own local data). If you want cross-device sync later, that needs a small backend — just ask and I can add one (e.g. free Supabase/Firebase).
- **Nobody else can see this.** It's not linked from anywhere and isn't searchable — only people with the exact URL can open it. If you want real privacy on a public GitHub repo, keep the repo name non-obvious, or ask me about adding a simple password gate.
- Works offline after the first load, thanks to the included service worker.
- To update the app later (e.g. change milestones), edit `index.html` and re-upload it to the same repo — GitHub Pages updates automatically within a minute.
