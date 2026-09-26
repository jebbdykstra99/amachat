# amachat

SubX room #19 — Great women of religious history — amas, nuns, and mothers of wisdom. (preview).

Static site. `siteId` is `amachat`. Custom domain in `CNAME` is `amachat.com`. Preview banner and `noindex` stay on.

Deploy `main` from `/` on GitHub Pages (Cloudflare DNS next). Factory shell talks to Firebase project `subx-skins` (fetches `firebase-web-config.json`; no API keys in this repo).

## Outside this repo

- Firestore allowlist for `siteId` `amachat` (CTO).
- Cloudflare zone + NS flip for `amachat.com` (CTO).
