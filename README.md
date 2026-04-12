# DLKR Text Editor

A minimal, single-file text editor with markdown preview, title case conversion, and clipboard tools. Deployed at [editor.thedlkr.com](https://editor.thedlkr.com).

## Features

- **Edit and preview** — write in markdown, preview rendered output
- **Case conversion** — UPPERCASE, lowercase, sentence case, and title case (AMA, AP, APA, Chicago, MLA styles) with brand name recognition
- **List formatting** — bullet and numbered lists
- **Sort and filter** — alphabetical, by length, deduplication
- **Clipboard tools** — copy as markdown, HTML, or rich text; paste HTML as markdown
- **File I/O** — open `.md`, `.txt`, `.html` files; drag-and-drop support
- **Undo/redo** — 50-step history with keyboard shortcuts
- **Auto-save** — content persists in localStorage
- **Dark and light themes** — preference saved across sessions
- **Live stats** — character, word, line, sentence, and paragraph counts

## Deployment

Static site hosted on GitHub Pages with a `CNAME` record pointing to `editor.thedlkr.com`. No build step required.

## Stack

- Vanilla HTML, CSS, JavaScript (single file)
- [Tailwind CSS](https://tailwindcss.com) (CDN)
- [Marked](https://marked.js.org) for markdown parsing
- [Turndown](https://github.com/mixmark-io/turndown) for HTML-to-markdown conversion
- [DM Sans + DM Serif Display](https://fonts.google.com/?query=dm) from Google Fonts
