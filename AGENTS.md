# AGENTS.md

## Cursor Cloud specific instructions

This repository is a **single-file, offline, client-side web app** (vanilla HTML/CSS/JS). There is no package manager, build step, backend, or automated test suite.

- The app is `index.html` (current release). `index-v1.html`, `index-v2.html`, `index-v3.html` are version history.
- All logic, styles, and the cartridge library are inlined in the HTML; there are no external/CDN dependencies and no network calls. It runs 100% offline in the browser.
- There is nothing to install. The update script is intentionally a no-op.
- To run it for development/testing, serve the repo root over HTTP and open the page, e.g. `python3 -m http.server 8000` then visit `http://localhost:8000/index.html`. (Opening the file directly also works since it is self-contained.)
- There is no lint or test command configured. "Building" is not applicable.
- State (rifle profiles) is persisted in browser `localStorage`, so it survives reloads but is per-browser.
