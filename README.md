# mukeshdelu.github.io

Personal academic website of **Dr. Mukesh Delu** — Assistant Professor of Mathematics,
Department of College Education, Government of Rajasthan.

A single, dependency-free `index.html` (light/dark theme, mobile responsive).

## Publish on GitHub Pages

1. Create a **public** repository named exactly `mukeshdelu.github.io`
   (the name must match the GitHub username, otherwise the site will not be served at the root domain).
2. Upload `index.html` (and this `README.md`) to the repository root.
3. Open **Settings → Pages**, set *Source* to **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. After a minute or two the site is live at <https://mukeshdelu.github.io>.

## Things to update

| What | Where in `index.html` |
| --- | --- |
| Portrait photo | the `<img class="portrait">` `src` — currently loaded from maitri-lab.com |
| New papers | add a `<li class="pub">` block in the Publications section |

## Optional: use a local copy of the photo

The portrait is currently hot-linked from `maitri-lab.com`. To make the site fully
self-contained, save the image as `photo.jpg` in this repository and change the `src` to `photo.jpg`.
