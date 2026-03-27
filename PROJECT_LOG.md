# Project Log — Octi Paper Website

**Project:** Octi single-page demonstration website (GitHub Pages, Markdown/Jekyll)  
**Local path:** `/home/katha/dev/octi-paper-website`  
**Intended repo name:** `octi-paper-website`  
**Intended hosting:** GitHub Pages (initially from `main` root for testing; later from `gh-pages` branch)  
**Tone:** Formal academic  
**Last updated:** 2026-03-22

---

## Purpose and scope

A modern, single-page website to accompany a research paper, demonstrating **Octi**, an LMS-integrated platform for collaborative writing analytics and feedback in higher education.

Octi comprises:
- **OctiPad**: collaborative editor with structured workspaces for real-time group writing
- **OctiFeedback**: scheduled, text-based feedback on collaborative processes

The website must include:
1. Octi logo (placeholder until provided)
2. A button linking to the standalone OctiPad instance: `https://octipad.s.studiumdigitale.uni-frankfurt.de/`
3. Screenshot sequences (placeholders for now):
   - OctiPad during the experiment (structured workspaces)
   - OctiFeedback examples
   with academic text blocks between figures
4. A concluding block on the same page: paper link (placeholder), citation (placeholder), contact (placeholder)

---

## Current implementation

**Single page**
- `index.md` contains the full narrative and figures.

**Layout and styling**
- `_layouts/default.html` provides header/footer and shared structure.
- `assets/css/site.css` provides a modern academic style, responsive figure layout, and buttons.

**Placeholders**
- `assets/images/placeholders/` contains SVG placeholders for logo and figures.

---

## Decisions

- Keep everything on a **single page**.
- Prefer a **simple GitHub Pages compatible** approach (no GitHub Actions).
- Use **placeholders** for logo and screenshots until final assets are provided.
- Anticipate GitHub Pages URL pattern for a project site:
  - `https://<username>.github.io/octi-paper-website/`

---

## GitHub workflow (second account)

Recommended approach when using multiple GitHub accounts:
- Set Git identity at the repository level (not necessarily global):
  - `git config user.name "..."`
  - `git config user.email "..."`

Publishing plan:
1. Create GitHub repo named `octi-paper-website` (do not auto-create README).
2. `git init` → commit → push.
3. Enable GitHub Pages: deploy from branch `main` and folder `/ (root)`.
4. Later: switch publishing to a `gh-pages` branch.

---

## Local preview (optional)

Docker-based Jekyll preview:

```bash
docker run --rm -it \
  -p 4000:4000 \
  -v "$PWD":/srv/jekyll \
  jekyll/jekyll:4 \
  jekyll serve --watch --force_polling --host 0.0.0.0
```

Open: `http://localhost:4000`

---

## Next inputs needed

- Final Octi logo
- OctiPad experiment screenshots (structured workspaces)
- OctiFeedback screenshots
- Paper URL (or DOI), final citation information, and contact details
