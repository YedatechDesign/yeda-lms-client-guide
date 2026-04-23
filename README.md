# Yeda LMS — Client Integration Guide

Static one-page documentation site for external partners and integrators connecting to **Yeda LMS**.

## 📄 What's inside

- `index.html` — single-page guide with sticky TOC, copy-paste recipes, syntax-highlighted code blocks, and a complete capability matrix.
- `assets/yeda-logo-blue.png` — brand mark.

## 🚀 Local preview

```bash
# Any static server will do:
python3 -m http.server 8080
# → open http://localhost:8080
```

## 🌐 Publishing on GitHub Pages

1. Push this repository to GitHub (already done via the Yedatech-design account).
2. In repository **Settings → Pages**, set:
   - **Source:** `main` branch, `/ (root)` folder.
3. After a minute or two, the site will be live at
   `https://<org-or-user>.github.io/<repo-name>/`.

## 🎨 Design

- **Colours** — navy `#000F61`, blue `#0A59EB`, soft-blue `#C4D8FD`, blue-bg `#F6F9FF`.
- **Fonts** — [Rubik](https://fonts.google.com/specimen/Rubik) for UI, [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) for code.
- **Syntax highlighting** — [Prism.js](https://prismjs.com/) (loaded from CDN).

The layout is intentionally minimalist — one hero, sticky left TOC, typography-first content area, and a plain footer. No animations or JavaScript besides the TOC active-section highlighter.

## 🔁 Updating the content

The HTML is hand-authored so it can be edited directly. All anchor ids are stable (`#getting-started`, `#user-tokens`, …) so deep links survive content edits.

If you'd rather regenerate from the upstream `.docx` / `.md` source, see `/Users/katedlugach/Library/Mobile Documents/com~apple~CloudDocs/Claude+/yeda-lms-api-docs/` (local).

## 🪪 Ownership

© Yeda. Internal/partner-facing documentation. Not for public distribution without consent.
