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
- `docs/` — documentation content (overview, hardware, software, safety, operations, testing, development, diagrams, appendix) plus custom theme assets.
- `.github/workflows/deploy.yml` — GitHub Pages deployment.
- `requirements.txt` — MkDocs dependencies.

## Contributing
- Theme: custom “red/orange on black” palette with light/dark toggle. Update colors in `docs/assets/styles/custom.css`. Logo lives at `docs/assets/images/gs-mark.png` (derived from `image.png`); `amalia.svg` is available for design cues.
- Keep diagrams current and referenced directly from text.
- Maintain traceability: requirements → design → tests → operations → revision history.
- Treat safety sections as authoritative; update procedures and interlocks together.
