# amachat

SubX room #19 — Great women of religious history — amas, nuns, and mothers of wisdom. (preview).

Static site. `siteId` is `amachat`. Custom domain in `CNAME` is `amachat.com`. Preview banner and `noindex` stay on.

Deploy `main` from `/` on GitHub Pages (Cloudflare DNS next). Factory shell talks to Firebase project `subx-skins` (fetches `firebase-web-config.json`; no API keys in this repo).

Catalog nests in `site.json` have a generated `<slug>.html` so `/<slug>` is HTTP 200. The stub uses the same restore handoff as `404.html`. Rooms added with + stay in `userNests` and are not stubbed. After editing catalog nests, regenerate with `python3 nest_stubs.py .`

## Outside this repo

- Firestore allowlist for `siteId` `amachat` (CTO).
- Cloudflare zone + NS flip for `amachat.com` (CTO).
