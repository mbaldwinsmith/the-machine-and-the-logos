# Project Notes for Contributors

## Background
- **The Machine and the Logos** is a three-act poetic stage play created collaboratively by Mark Baldwin-Smith and ChatGPT.
- The work explores the meeting point of human creativity, artificial intelligence, and divine Wisdom, presenting their dialogue across creation, temptation, and transfiguration.
- The repository supports literary reading, theatrical performance, and contemplative meditation; keep changes aligned with the play's contemplative, reverent tone.

## Repository Structure
- `README.md` — high-level overview, themes, authorship, and performance guidance.
- `index.md` — the full script, arranged with YAML front matter, dedication, preface, dramatis personae, acts, appendices, and production appendices.
- `performance-notes.md`, `music.md`, `about.md`, and `postscript.md` — supplemental reflections and staging aids.
- `_layouts/` — Jekyll layout templates; the default layout powers the published script page.
- `assets/` — media assets referenced by the Markdown content (e.g., the fractal cross image in the script header).
- `_config.yml` — Jekyll configuration (site metadata, collections, etc.).

## Contribution Guidance
- Preserve the existing structure of acts and appendices; if extending the play, clearly mark new sections and maintain thematic coherence.
- When editing Markdown that feeds the static site, ensure front matter remains valid and internal links use Jekyll-relative paths.
- Image assets should be placed in `assets/` and referenced with `{{ '/path' | relative_url }}` to maintain compatibility with Jekyll deployments.

