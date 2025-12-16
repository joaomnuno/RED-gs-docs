# Groundstation Documentation

MkDocs-based documentation skeleton for the hybrid rocket groundstation. It follows an operator/engineer/reviewer structure with safety-forward emphasis.

## Quick start
```bash
pip install -r requirements.txt
mkdocs serve
```
Open http://127.0.0.1:8000 to preview.

## Structure
- `mkdocs.yml` — site config and navigation.
- `docs/` — documentation content (overview, hardware, software, safety, operations, testing, development, diagrams, appendix).
- `.github/workflows/deploy.yml` — GitHub Pages deployment.
- `requirements.txt` — MkDocs dependencies.

## Contributing
- Keep diagrams current and referenced directly from text.
- Maintain traceability: requirements → design → tests → operations → revision history.
- Treat safety sections as authoritative; update procedures and interlocks together.
