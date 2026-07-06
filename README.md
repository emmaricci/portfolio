# Portfolio site

Static one-page site. No build step, no dependencies beyond CDN fonts and icons.

## Files

- `index.html` — all content and structure
- `styles.css` — palette, type, layout
- `script.js` — mobile nav toggle, footer year
- `assets/` — put your headshot and CV PDF here

## Before you publish, fill in

Search the codebase for `TODO` and `#` placeholder links. Specifically:

1. **Headshot** — add `assets/headshot.jpg` (square, at least 200x200px)
2. **CV** — add `assets/cv.pdf`, or point the CV nav link somewhere else
3. **Social links** — Google Scholar, LinkedIn, Instagram URLs in the header
4. **Email** — replace `you@example.com` in two places (header icon, footer)
5. **Publications** — every row past the Journal of Affective Disorders Reports
   entry is a placeholder. Confirm exact titles, co-author order, and add DOI
   or arXiv links before this goes live to recruiters.
6. **Project links** — the two project cards link to `#`; point them at live
   demos, Figma prototypes, or case study write-ups if you have them.

## Running locally

Just open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploying to GitHub Pages

1. Push this folder to a GitHub repo (either the repo root, or a `/docs`
   folder — adjust the Pages source setting to match)
2. Repo → Settings → Pages → Source: deploy from the branch containing these
   files
3. Site will be live at `https://<username>.github.io/<repo-name>/`

If you want it at `https://<username>.github.io` directly (no repo name in
the URL), name the repo `<username>.github.io` and put these files at its
root.

## Design notes

Palette: mist `#fcf9f2` background, coal `#231f20` body text, cacao `#603620`
(currently unused, reserved if you want a third accent), moss `#63703d` as
the single link and accent color, meadow `#b5c37c` for tag and card fills.

Type: Fraunces (serif, display and intro paragraph), Inter (body and UI),
IBM Plex Mono (labels, dates, tags).
