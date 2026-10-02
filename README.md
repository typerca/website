# typerca.io

The TypeRCA website. Plain HTML, CSS and JavaScript, no build step.

- `site/` is published as-is to https://typerca.io by `.github/workflows/pages.yml` on every push to `main` that touches it.
- `site/data/incidents.json` (the home page replay) is generated from the recorded live runs; regenerate it in the main TypeRCA repo and copy it here.

Preview locally: `python3 -m http.server -d site 8000`, then open http://localhost:8000.
