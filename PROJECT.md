---
title: html-website-donathan
type: html-website
status: dormant
---

# html-website-donathan

## Description

Source repo for the personal site at https://donathan.us. Vanilla HTML + CSS, no build step. Deploys to GitHub Pages via Actions; `CNAME` maps to the apex domain. Contents: `index.html`, `styles.css`, `CNAME`, `README.MD`, `.vscode/extensions.json`. Remote: `github.com/ndonathan/website`.

## SDLC compliance

### Universal floor
- [x] README.md (`README.MD`)
- [x] PROJECT.md
- [ ] TODO.md (open: add `.gitignore`, README typo)
- [ ] .gitignore

### Project-specific (html-website)
- [x] index.html
- [x] styles.css
- [x] CNAME
- [x] GitHub Pages deployment via Actions

## Notes

- Consolidated on 2026-05-02 from two folders (`html-website-donathan` and `html-website-donathan-publishclone`). The donathan folder's local-only WIP was a stale rebuild of work already present on this clone + remote, so it was discarded; this clone (formerly `…-publishclone`) was rebased onto origin/main and renamed to take over the `html-website-donathan` name.
- Drive-by observation from the remote `bada6e4 small changes` commit: `README.MD` contains the typo "crezy" (should be "crazy"). Captured in `TODO.md`.
