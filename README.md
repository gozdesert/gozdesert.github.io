# Gözde Sert — academic portfolio

This repository publishes [gozdesert.github.io](https://gozdesert.github.io/). The website is made of plain HTML and CSS, so it can be edited on a local computer without installing Jekyll or a build tool.

## Edit on your computer

1. Clone this repository to your computer with GitHub Desktop (or open an existing local clone and pull the latest changes).
2. Open the `site` folder. Edit `site/index.html` for the home page, `site/publications/index.html` for publications, `site/teaching/index.html` for teaching, and `site/cv/index.html` for the résumé page.
3. Change the shared colors, spacing, and typography in `site/styles.css`. Replace `site/portrait.jpg` to update the photo.
4. Open `site/index.html` in a browser for a quick preview. To preview every page with the same paths used online, run `python3 -m http.server 8000 --directory site` and visit `http://localhost:8000/`.
5. In GitHub Desktop, commit your changes and push to `main`. The workflow in `.github/workflows/deploy.yml` updates the existing `gh-pages` branch, which keeps the same website address.

The old al-folio/Jekyll source remains available in this repository's Git history. This replacement branch removes those files to make future edits simpler. If the GitHub Pages settings currently publish from `gh-pages`, keep that setting.

## Before first publication

Review the title, affiliation, email, publication status, awards, and teaching entries. They were copied from the previously published site, which may need updates. The résumé page continues to request contact by email; no PDF is published.
