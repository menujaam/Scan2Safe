# Scan2Safe

> ⚠️ **Prototype v0.1 — first working prototype.**
> This is an early proof of concept, not a production release. Expect rough edges, incomplete features, and breaking changes.

Scan2Safe is a Progressive Web App (PWA) for **fire extinguisher safety inspections**. Inspectors photograph an extinguisher, and the app walks through an 8-step photo-based check, using the Claude vision API to analyse each image.

## What's in this prototype

- 8-step guided photo inspection of fire extinguishers
- AI image analysis via the Anthropic Claude API
- Dashboard view of inspections
- Installable as a PWA (home-screen icon, standalone display, portrait layout)
- Basic offline support — the app shell is cached by a service worker and an offline page is shown when there's no connection (AI analysis still requires internet)

