# Hushdrop — Brand Guidelines

Everything you need to represent Hushdrop correctly. Assets are served from
`https://hushdrop.dev/_brand/` and the SVG sources live in [`brand/`](brand/).

---

## Name

- The product is **Hushdrop** — one word, capital **H**, lowercase rest. Never "HushDrop", "Hush Drop", or "hushdrop" mid-sentence (lowercase only in code, URLs, and the npm/CLI namespace).
- The CLI command is **`hush`** (e.g. `hush report.html`). The npm packages are `hushdrop`, `hushdrop-mcp`, `hushdrop-cli`, `hushdrop-install`.
- Domain: **hushdrop.dev**.

## Logo

The mark is a **drop with a keyhole** — *drop* (the action of dropping/sharing an artifact) + *hush* (private, zero-knowledge). The keyhole is a transparent cut-out, so the mark sits on any background.

| Asset | Use | File |
|---|---|---|
| Mark (color) | default, on dark | [`/_brand/logo-mark.svg`](https://hushdrop.dev/_brand/logo-mark.svg) · [PNG](https://hushdrop.dev/_brand/logo-mark-512.png) |
| Mark (white) | single-color on dark/photo | [`/_brand/logo-mark-white.svg`](https://hushdrop.dev/_brand/logo-mark-white.svg) |
| Mark (black) | single-color on light | [`/_brand/logo-mark-black.svg`](https://hushdrop.dev/_brand/logo-mark-black.svg) |
| Lockup (light text) | mark + wordmark on **dark** bg | [`/_brand/logo-lockup-dark.png`](https://hushdrop.dev/_brand/logo-lockup-dark.png) |
| Lockup (dark text) | mark + wordmark on **light** bg | [`/_brand/logo-lockup-light.png`](https://hushdrop.dev/_brand/logo-lockup-light.png) |
| App icon | avatar, favicon, app tile | [`/_brand/icon-512.png`](https://hushdrop.dev/_brand/icon-512.png) · [256](https://hushdrop.dev/_brand/icon-256.png) |
| Favicon | browser tab | [`/_brand/favicon.png`](https://hushdrop.dev/_brand/favicon.png) |
| OG / social card | link previews | [`/_brand/og.png`](https://hushdrop.dev/_brand/og.png) |

**Clear space:** keep padding ≥ the width of the keyhole around the mark. **Minimum size:** 16px (favicon) for the mark; use the app-icon (mark in a rounded square) below 24px for legibility.

**Don't:** recolor the mark (outside the approved white/black mono), add effects beyond the subtle orange glow, stretch it, rotate it, box the color mark on a busy photo (use the white mark or the app-icon instead), or rebuild the wordmark in a different typeface.

## Color

| Token | Hex | Use |
|---|---|---|
| Primary (orange) | `#ff6b35` | brand, accents, links, the mark (gradient start) |
| Accent (deep orange) | `#ea580c` | gradient end, hovers |
| Ink | `#0b0b0d` | primary dark background |
| Ink-2 | `#0a0a0c` | site background base |
| Foreground | `#e9edf5` | text on dark |
| Dim | `#8b93a7` | secondary text |

The mark uses a 135° linear gradient `#ff6b35 → #ea580c`.

## Typography

- **Brand & UI:** monospace — `ui-monospace, "SF Mono", "JetBrains Mono", Menlo, Consolas, monospace`. The wordmark "Hushdrop" is mono, weight 800, letter-spacing -0.03em.
- **Long-form copy:** system sans — `-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif`.

## Voice

Direct, technical, honest, a little dry. We name the pain before the pitch, and we don't overclaim (e.g. the hosted connector is *not* zero-knowledge — say so).

**Taglines**
- Primary (pain-first): **"Your AI's work shouldn't die in a chat."**
- Hero (long): "Your AI just built something great — now it's trapped in a chat window."
- Descriptor / SEO: "Open-source artifact sharing for AI agents — a private, branded link on your own domain."
- One-liner: "The share button your AI agents are missing."

## One-line description

> Hushdrop turns anything your AI builds — a report, dashboard, or app — into a private, branded, zero-knowledge link on your own domain, in ~1 second, from any agent. Open-source, MIT.

---

*Questions / asset requests: [hushdrop.dev](https://hushdrop.dev) · [github.com/maxtechera/hushdrop](https://github.com/maxtechera/hushdrop)*
