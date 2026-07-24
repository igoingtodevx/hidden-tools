# Hidden Tools — Nexus

A responsive friends-and-family utility hub reconstructed from the supplied 12ui cosmic composition as real HTML, CSS and JavaScript.

## Included now

- Animated cosmic landing page and responsive tool constellation
- Quick-launch command palette, filters and keyboard navigation
- Local image compression
- JSON formatter and minifier
- Cryptographically secure password generator
- Local link vault
- Timestamp/date converter
- Local SHA-256 file fingerprinting
- Local text cleaner and transformer
- yt-dlp command builder for content the user is authorized to download
- Preview slots for custom AI rooms and a future permissioned family knowledge base

## Vercel

This is a static site. Import the repository root with no framework preset and no build command. `vercel.json` adds privacy and baseline security headers.

## Privacy and API keys

The local tools process their data in the browser. The AI tools are intentionally placeholders until protected server-side API routes are added. Never place provider API keys in `app.js`.

`noindex` and `robots.txt` reduce search-engine discovery, but they are not authentication. Enable Vercel Deployment Protection or add a real authentication layer before storing private information or sharing paid APIs.
