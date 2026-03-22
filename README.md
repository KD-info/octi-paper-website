# Octi paper website (single page)

This repository contains a single-page, markdown-first website for a research paper demonstration of **Octi**.

The page presents:
- A placeholder logo (to be replaced with the final Octi logo)
- A button linking to the standalone OctiPad instance
- Placeholder figures for OctiPad structured workspaces and OctiFeedback examples
- Academic, figure-caption style explanatory text blocks between images

## Repository structure
- `index.md` — the single-page content
- `_layouts/default.html` — minimal layout with header + footer
- `assets/css/site.css` — styling (responsive figures, buttons, typography)
- `assets/images/placeholders/` — SVG placeholders for the logo and figures

## Replace placeholders with real assets
Keep the filenames and paths stable, and simply replace the placeholder files:
- `assets/images/placeholders/octi-logo.svg`
- `assets/images/placeholders/octipad-workspace-01.svg` (and `-02`, `-03`)
- `assets/images/placeholders/octifeedback-01.svg` (and `-02`, `-03`)
- `assets/images/placeholders/fig-01-system-overview.svg`

You may replace SVG placeholders with PNG/JPG; if you do, update the file extension in `index.md` and `_layouts/default.html`.

## Local preview (optional)
GitHub Pages builds Jekyll automatically. For local preview you can use Docker to avoid Ruby setup:

```bash
docker run --rm -it \
  -p 4000:4000 \
  -v "$PWD":/srv/jekyll \
  jekyll/jekyll:4 \
  jekyll serve --watch --force_polling --host 0.0.0.0
```

Then open `http://localhost:4000`.

## GitHub Pages publishing
For initial testing, you can publish from the repository root.
When moving to a `gh-pages` branch later, keep the same file structure.

If this becomes a *project site* (URL like `https://<user>.github.io/<repo>/`), set these in `_config.yml`:

```yml
url: "https://<user>.github.io"
baseurl: "/<repo>"
```

The site uses Jekyll’s `relative_url` filter for asset paths, so it will work correctly once `baseurl` is set.
