# Kingshot Guide (MkDocs)

This repository contains a MkDocs site using the Material theme for a Kingshot mobile game event guide.

## Develop locally

1. Create/activate a Python 3.10+ virtual environment.
2. Install dependencies from `requirements.txt`.
3. Serve the site locally.

### Quick start
```
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Then open http://127.0.0.1:8000 in your browser.

## Structure
- `mkdocs.yml` – site config and navigation
- `docs/` – Markdown content
  - `index.md` – overview
  - `events/` – event-specific pages

## Notes
- Halls of Governors includes tabs for F2P and spenders using Material tabs.
