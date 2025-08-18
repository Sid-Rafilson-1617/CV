# Sid Rafilson — Research CV (Jekyll)

This is a minimal Jekyll site (GitHub Pages-ready) to host a clickable academic CV with publications, posters, and presentations.

## Local Preview

```bash
bundle install
bundle exec jekyll serve
```
Then open http://127.0.0.1:4000

## Add your PDFs / Slides
Place poster PDFs in `assets/posters/` and slide decks in `assets/slides/`, then update the `poster:` and `slides:` fields in each item under `_presentations/`. For publications, add `pdf:` and `doi:` links inside each file in `_publications/`.

## Add new items
Create a new Markdown file under `_publications/` or `_presentations/` with front matter like the examples here.

