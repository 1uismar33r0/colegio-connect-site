# Colegio Connect project page

Static project web page for the Colegio Connect capstone (UPRM, Fall 2026). No build step.

## Contents

- `index.html` — the page
- `screenshots/` — main branch (f0c4efe) captured Nov 10, 2026 (Puerto Rico time) against an isolated local stack with synthetic demo data
- `wireframes/` — four-role wireframes from `docs/Wireframes` on the `Issue-13-Wireframes` branch
- `docs/` — approved proposal and progress report (v4)

## Publish with GitHub Pages

```bash
gh repo create colegio-connect-site --public --source . --push
gh api -X POST repos/1uismar33r0/colegio-connect-site/pages -f "source[branch]=main" -f "source[path]=/"
```

The page will be served at https://1uismar33r0.github.io/colegio-connect-site/ within a few minutes.
