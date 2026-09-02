# Cambridge English School — Website

A simple static site: `index.html` + `style.css` + `assets/`. No build step needed.

## Host it free on GitHub Pages

1. Create a new GitHub repository (e.g. `cambridge-english-school`).
2. Upload these three items to the repo root: `index.html`, `style.css`, and the `assets` folder.
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
5. Wait a minute, then your site will be live at:
   `https://<your-github-username>.github.io/cambridge-english-school/`

   (If you name the repo `<your-github-username>.github.io` instead, the site will be live at the root of that URL with no extra path.)

## Adding real photos

The "Campus Life" section on the homepage currently shows placeholder tiles. To add real photos:

1. Put your photos in `assets/gallery/` (create the folder).
2. In `index.html`, find the `<div class="gallery-grid">` section and replace each
   `<div class="gallery-tile"><span>Label</span></div>`
   with an `<img>` tag, e.g.:
   `<img src="assets/gallery/assembly.jpg" alt="Morning assembly">`

## Editing content

Everything is in plain HTML in `index.html` — address, phone number, vision/mission text, founder bio, etc. Just open the file in any text editor and edit the text between the tags.
