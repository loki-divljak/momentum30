# Momentum 30 — Anytime Fitness Newcastle Region

**Small actions. Big results.**

Member onboarding journey app for Anytime Fitness Newcastle Region clubs.
Single-file web app — no build step, no dependencies, no backend required.

© 2025 Anytime Fitness Newcastle Region / Fitness Group Holdings. All rights reserved.
Proprietary and confidential. Unauthorised use, reproduction or distribution is prohibited.

## Files in this repository

| File | Purpose |
|------|---------|
| `index.html` | The complete app (HTML + CSS + JS) |
| `manifest.json` | Enables "Install to Home Screen" on Android |
| `icon-192.png` | App icon (home screen, small) |
| `icon-512.png` | App icon (home screen, large) |

## Deploy on GitHub Pages (5 minutes)

1. Create a new **public** GitHub repository (e.g. `momentum30`)
2. Upload all files from this folder to the repository root
   (GitHub web UI: "Add file" → "Upload files" → drag-and-drop all 4 files)
3. Go to **Settings → Pages**
4. Source: "Deploy from a branch" → Branch: `main` → Folder: `/ (root)` → Save
5. Your live URL will appear within ~60 seconds:
   `https://YOUR-USERNAME.github.io/momentum30/`
6. Test on iPhone (Safari) and Android (Chrome) to confirm
7. Generate a QR code pointing to that URL

## Updating the app

Edit `index.html` in the GitHub web UI (click the pencil icon).
GitHub Pages redeploys automatically within ~60 seconds.
**The QR code URL never changes** — members don't need to re-scan.

## Club customisation

The app includes a club selector on first launch:
- Anytime Fitness Newcastle
- Anytime Fitness Kotara
- Anytime Fitness Edgeworth
- Anytime Fitness Thornton
- Anytime Fitness Greenhills
- Anytime Fitness Lake Haven

To add or rename clubs, search for `CHECKLIST` in `index.html`
and update the `<option>` values in the setup screen.

## Custom domain (optional)

For a branded URL like `momentum30.anytimefitnessnewcastle.com.au`:
1. Purchase domain (~$15/year)
2. Settings → Pages → Custom domain → enter domain → Save
3. Add the DNS records shown at your registrar
4. Enable "Enforce HTTPS" after certificate provisions
