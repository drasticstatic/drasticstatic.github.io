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

---

## Commit Convention

Full fleet convention, shown here regardless of whether this specific repo currently has an Augment
Intent workspace pairing or NIM in active use — so a new repo (and its memory) doesn't need the
whole multi-agent suite re-explained from scratch. Which *application* launched a session decides
the agent name and engine, not which path — see
`anthropas-argus-alfred/sandbox/AGENT_IDENTITY_REFERENCE.md` and `INTENT_WORKTREE_LEGEND.md` for
the full rule.

- Alfred-Anthropic: `Co-Authored-By: Alfred · ClaudeCodeCLI · Anthropic [Sonnet-5/Opus-#/Haiku-#]`
- Alfred-NIM: `Co-Authored-By: Alfred · ClaudeCodeCLI · NVIDIA NIM [model]`
- Kavanah-AugmentIntentUI-AuggieLogin: `Co-Authored-By: Kavanah · AugmentIntent · [model]`
- Kavanah-AugmentIntentUI-AnthropicLogin ("ClaudeMent"): `Co-Authored-By: Kavanah · ClaudeMent · Anthropic [model]`
- Kavanah-TerminalUI(macOS/Intent/VSCode standard terminal instance)-AnthropicLogin: `Co-Authored-By: Kavanah · ClaudeCodeCLI · Anthropic [model]`
- Mystarch (app-level Chief of Staff, cross-workspace reach): same engine options as Kavanah above, swap the agent name
- Auggie (native Augment CLI — currently hibernating, may return): `Co-Authored-By: Auggie · AugmentCLI · [model]`
