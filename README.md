# Atlas of Humans × AI (prototype)

A map of studies on how AI affects people, with the direction of each effect (enhances, mixed, diminishes, transforms, no effect, not stated).

- `index.html` is the atlas. It reads `atlas_data.js`.
- `explorer.html` is a group explorer over the same sample. It reads `dataset_v2.js`.
- Everything is static. Open `index.html` in a browser, or serve the folder (`python3 -m http.server`).

## What the data is
A 1,000-work sample of a 57,741-work index built from OpenAlex. Groups, direction and study type were produced by Claude from titles and abstracts and have **not been verified by a person**. Only titles, authors, venues, years and DOIs are included, never abstracts.

## Publishing on GitHub Pages
Settings → Pages → Build and deployment → Deploy from a branch → `main` / root.
