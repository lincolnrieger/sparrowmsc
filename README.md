# Sparrow — website

Static site for Sparrow, experimental grunge from Adelaide. Plain HTML, no build step.

## Files
- `index.html` — the whole site
- `shows.js` — **the gig list. Edit this file to add or remove shows.**
- `images/` — all photos

## Put it online with GitHub Pages
1. Create a new repository on GitHub (e.g. `sparrow-website`).
2. Click **Add file → Upload files**, drag in everything from this folder (including the `images` folder), then **Commit changes**.
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, pick `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://YOUR-USERNAME.github.io/sparrow-website/`.

## Updating shows
Option A — on GitHub: open `shows.js`, click the pencil icon, edit, **Commit changes**.
Option B — download `shows.js`, edit it in any text editor (Notepad, TextEdit), then
**Add file → Upload files** on GitHub and upload it again (it replaces the old one).

Upcoming and past shows sort themselves by date.

## Other edits
To swap a photo, replace the file in `images/` with one of the same name.
