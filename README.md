# Atlas of Humans × AI (prototype)

A map of studies on how AI affects people, with the direction of each effect (enhances, mixed, diminishes, transforms, no effect, not stated).

- `index.html` is the atlas. It reads `atlas_data.js` (the 11,007 studies of AI's effect on people) and, when you open the Topic & technology view, `atlas_v1_rest.js` (the other works, so that view covers all 57,741).
- `methods.html` explains where the studies come from, how they were coded and grouped, and the limits.
- Everything is static. Open `index.html` in a browser, or serve the folder (`python3 -m http.server`).

## What the data is
A 57,741-work index built from OpenAlex. Every work was read by Claude (Haiku 5.5) from its title and abstract, which produced the direction, study type, one-sentence finding and the groups you see. Group names were drafted by Claude and some were written by hand; the project lead regrouped some themes by hand. **None of it has been verified by a person.** Only titles, authors, venues, years, DOIs and the model-written fields are included, never abstracts.

## Corrections
sns46@cam.ac.uk

## Publishing on GitHub Pages
Settings → Pages → Build and deployment → Deploy from a branch → `main` / root.
