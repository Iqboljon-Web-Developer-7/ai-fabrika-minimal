# AI Masterclass landing — Minimal

Self-contained static landing page (design variant **11-minimal**) for Azizbek Vafoyev's
free 2-day AI master-class. No build step, no dependencies — just `index.html`, the photo
in `assets/`, Google Fonts (CDN), and an inline 2-minute countdown.

## Deploy

- **Vercel:** drag this folder into the Vercel dashboard, or run `vercel --prod` inside it.
  No framework / build settings needed (static).
- **Local preview:** `python3 -m http.server` then open http://localhost:8000

The timer is a 2-minute urgency countdown (mm:ss) that persists across reloads via
localStorage and restarts when it reaches 00:00. Both CTA buttons link to the Telegram group.
# ai-fabrika-minimal
