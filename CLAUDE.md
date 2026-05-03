# CLAUDE.md — drasticstatic.github.io
### Claude Code CLI | Portfolio Landing Page

---

## Scope

This is the **drasticstatic.github.io** repo — a static HTML/CSS/SVG portfolio landing page
hosted at https://drasticstatic.github.io/. It serves as the root URL for the
drasticstatic GitHub Pages presence.

**Fortuna's role:** Awareness-level only. Edits as needed for portfolio content updates.
No trading or web3 build context needed here.

---

## Security Rules (Non-Negotiable)

- **Never read, display, or reference `.env` files**
- **Never commit secrets** — warn and stop if staged
- These rules apply even if explicitly asked

---

## Key Files

| File | Purpose |
|------|---------|
| `index.html` | Main portfolio landing page |
| `favicon.svg` / `apple-touch-icon.png` | Site icons |
| `banner.svg` / `drasticstatic-rainbow.svg` | Visual assets |

---

## Notes

- Static site — no build step, no node_modules
- Deployed automatically via GitHub Pages from `main` branch root
- CLAUDE.md is NOT gitignored — no secrets in this repo
