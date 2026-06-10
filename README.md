# Mark Kerssenfischer — academic homepage

Source for the personal academic website, hosted on **GitHub Pages**.
Plain static HTML/CSS — no build step, no generator.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The whole site (single page, semantic sections). |
| `assets/style.css` | Styling. |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (no Jekyll). |
| `*.pdf`, `*.xlsx`, `*.bib` | Papers, slides, datasets, BibTeX — linked directly from `index.html`. |

## How to add a publication

In `index.html`, find the `#publications` section and copy one `<article class="pub"> … </article>`
block. Update the title, `pub-meta` (authors / journal / year), `pub-abstract`, and the links in
`pub-actions`. PDF links are **relative** to the repo root, e.g. `href="MyPaper.pdf"`, so just drop
the PDF in the repo root and reference its filename.

Working papers live in the `#working-papers` section and use the same block structure.

## Deploying

GitHub Pages serves the `main`/`master` branch root. After merging changes there, the live site
updates automatically within a minute or two. See the deployment notes that accompanied the initial
setup for first-time configuration and (optional) custom-domain setup.
