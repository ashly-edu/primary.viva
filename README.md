# ANZCA Viva Tracker — PWA

A mobile-first Progressive Web App for tracking ANZCA Primary exam viva topics with spaced repetition.

## Files
- `index.html` — main app
- `manifest.json` — PWA manifest
- `sw.js` — service worker (offline support)
- `icon-192.svg` / `icon-512.svg` — app icons

## How to host (free options)

### Option A: GitHub Pages (recommended)
1. Create a free GitHub account at github.com
2. Create a new repository (e.g. `viva-tracker`), set it to Public
3. Upload all 5 files
4. Go to Settings → Pages → Source: Deploy from branch → main → / (root)
5. Your app will be live at `https://yourusername.github.io/viva-tracker`
6. Open that URL on your phone → Safari/Chrome menu → "Add to Home Screen"

### Option B: Netlify Drop (easiest, no account needed)
1. Go to https://app.netlify.com/drop
2. Drag the entire folder onto the page
3. You'll get a URL like `https://random-name.netlify.app`
4. Open on phone → Add to Home Screen

### Option C: Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in this folder
3. Follow prompts — you'll get a live URL

## Adding to Home Screen

### iPhone (Safari)
1. Open the app URL in Safari
2. Tap the Share button (box with arrow)
3. Scroll down → "Add to Home Screen"
4. Tap "Add"

### Android (Chrome)
1. Open the app URL in Chrome
2. Tap the three-dot menu
3. Tap "Add to Home screen" or "Install app"
4. Tap "Add"

The app works fully offline once installed. Your data is stored locally on your device.
Use Export JSON regularly to back up your data.
