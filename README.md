# Archana Jha portfolio

A static portfolio site: plain HTML and CSS, no build step.

## Files

- `index.html` holds all the content.
- `styles.css` holds the design. Edit the color variables at the top of `:root` to re-theme the site.
- `assets/resume.pdf` is the file behind the Resume buttons. Replace it with a newer PDF and keep the same file name.
- `assets/agentic-research-lab-workflow.svg` is the workflow diagram.
- `.nojekyll` tells GitHub Pages to serve the files as they are.

## Deploy on GitHub Pages

1. Create a new repository, for example `portfolio`, and upload everything in this folder to its root.
2. In the repository, open Settings, then Pages.
3. Under Build and deployment, set Source to "Deploy from a branch", choose the `main` branch and the `/ (root)` folder, then save.
4. After a minute or two the site is live at `https://arjha10-max.github.io/portfolio/`.

To get the shorter address `https://arjha10-max.github.io/`, name the repository `arjha10-max.github.io` instead.

## Preview locally

From this folder, run `python3 -m http.server 8000` and open http://localhost:8000.
