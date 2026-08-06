# Octi paper website (single page)

This repository contains a single-page, markdown-first website for a research paper demonstration of **Octi**.

## Use of images and screenshots

Unless explicitly stated otherwise, **all screenshots, figures, and images contained in this repository and/or displayed by the generated website are provided for viewing in the context of the Octi demonstration only**. They may not be reused, redistributed, or republished (in whole or in part) without prior written permission from the project owners and/or respective rights holders.

The page presents:
- A placeholder logo (to be replaced with the final Octi logo)
- A button linking to the standalone OctiPad instance
- Placeholder figures for OctiPad structured workspaces and OctiFeedback examples
- Academic, figure-caption style explanatory text blocks between images

## Project notes
- `PROJECT_LOG.md` — decisions, structure, and publishing notes
- `CHAT_EXPORT.md` — paste/exported chat transcript for continuity

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

## Local preview
GitHub Pages builds Jekyll automatically. For local preview, use one of the options below.

### Option A: Docker (recommended when available)

Run from the repository root:

```bash
docker run --rm -it \
  -p 4000:4000 \
  -v "$PWD":/srv/jekyll \
  jekyll/jekyll:4 \
  jekyll serve --watch --force_polling --host 0.0.0.0
```

If Docker shows a permission error for `/var/run/docker.sock`, your user is not in the `docker` group on that machine. Either request access from the system administrator or use Option B below.

### Option B: No-sudo setup with Conda (works on restricted servers)

Create a local environment and install Jekyll entirely in user space:

```bash
conda create -y -n jekyll-preview ruby
conda install -y -n jekyll-preview -c conda-forge compilers make
conda run -n jekyll-preview gem install bundler jekyll
```

Start the local server:

```bash
conda run --no-capture-output -n jekyll-preview \
  jekyll serve --watch --force_polling --host 0.0.0.0 --port 4000
```

### Open the site locally

With the current `_config.yml` (`baseurl: "/octi-paper-website"`), open:

```text
http://localhost:4000/octi-paper-website/
```

If `baseurl` is changed to an empty string, use:

```text
http://localhost:4000/
```

Stop the local server with `Ctrl+C`.

## GitHub Pages publishing
For initial testing, you can publish from the repository root.
When moving to a `gh-pages` branch later, keep the same file structure.

If this becomes a *project site* (URL like `https://<user>.github.io/<repo>/`), set these in `_config.yml`:

```yml
url: "https://<user>.github.io"
baseurl: "/<repo>"
```

The site uses Jekyll’s `relative_url` filter for asset paths, so it will work correctly once `baseurl` is set.
