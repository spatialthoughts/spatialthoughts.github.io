# Geospatial Portfolio Template

A ready-to-use portfolio website template for geospatial professionals — GIS analysts, remote
sensing specialists, spatial data scientists, and GeoAI practitioners. Built with
[MkDocs](https://www.mkdocs.org/) and the [Material theme](https://squidfunk.github.io/mkdocs-material/).

**[SEE LIVE DEMO](https://spatialthoughts.github.io/portfolio-website-template/)**

---

## What's Included

- **Home** — Profile photo, bio, social links, skill cards, and CV download button
- **Projects** — Image card gallery with individual project pages; supports both Markdown and Jupyter notebooks
- **Resources** — Card grid linking to external teaching and learning resources
- **Publications** — Journal articles, conference papers, theses, and reports
- **Experience** — Work history, education, and certifications
- **Contact** — Links and CV download
- Auto-deploy to GitHub Pages on every push to `main`
- Light/dark mode toggle
- Mobile-responsive layout

---

## Quick Start

See **[SETUP.md](SETUP.md)** for the full step-by-step guide, including:

- Forking this template on GitHub
- Enabling GitHub Pages
- Editing content in the GitHub web editor (no local install needed)
- Setting up a local development environment with conda

---

## Adding Jupyter Notebook Projects

Jupyter notebook support is included by default via `mkdocs-jupyter`. Drop your `.ipynb`
file into `docs/projects/` and add it to the nav in `mkdocs.yml`:

```yaml
nav:
  - Projects:
    - "All Projects": projects/index.md
    - "My Notebook Analysis": projects/my-analysis.ipynb
```

Cell outputs (maps, charts, tables) render inline on the published site.

---

## License

[MIT License](LICENSE)
