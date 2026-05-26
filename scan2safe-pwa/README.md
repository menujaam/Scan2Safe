# Scan2Safe PWA

A Progressive Web App for fire extinguisher safety inspections.

## What it does

- Scan a QR code to identify a fire extinguisher
- Complete an 8-step photo inspection (safety pin, nozzle, seal, gauge, labels, body, expiry date, housekeeping)
- View pass/fail results and inspection history on the dashboard
- Installable on any device — works like a native app from the browser

## Using the app

Open the hosted URL in any modern browser. On mobile you will be prompted to **Add to Home Screen** to install it as a PWA.

## Hosting it yourself

This is a folder of static files — no server or build step needed.

**Cloudflare Pages**
1. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
2. Create a project → Upload assets
3. Drag and drop this entire folder

**GitHub Pages**
1. Push this folder to a GitHub repository
2. Go to Settings → Pages → set source to the branch/root
3. Your app will be live at `https://<username>.github.io/<repo>`

**Any static host** (Netlify, Vercel, S3, etc.)
Upload the folder contents — `index.html` is the entry point.

## Notes

- This is a demo build — inspection photos are not sent anywhere and all steps return a passing result
- No API keys or backend required
- All data is stored locally in the browser (resets on clear)
