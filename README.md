# Aryan × Zoomies: portfolio site

A static site with no build step. Vercel serves it as it is.

## Add your photos
Drop these files into `images/`. Until a photo is added, the site shows an illustrated placeholder in its place.

| File | Where it shows | Best shape |
|---|---|---|
| `images/hero.jpg` | Hero (you with your pets) | Portrait, 4:5 |
| `images/pet-1.jpg` | "The crew", first tile | Square |
| `images/pet-2.jpg` | "The crew", second tile | Square |
| `images/pet-3.jpg` | "The crew", third tile | Square |

Keep each photo under ~400 KB so the page loads fast on phones.

## Personalise
At the top of the `<script>` block in `index.html`, edit `CONFIG`:
- `captions`: names under the three crew photos, e.g. "Bruno, 4, chief treat officer"
- `story`: your own pet story in 1–2 sentences, which replaces the default line in "My pet story"

## Deploy on Vercel
- Dashboard: go to vercel.com, choose Add New, then Project, then upload this folder or import it from GitHub. Set Framework to "Other". Leave the build command empty.
- CLI: run `npx vercel` and then `npx vercel --prod` from inside this folder.
