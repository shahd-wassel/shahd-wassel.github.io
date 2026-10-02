# Shahd Wassel - Portfolio Website

Static site (HTML, CSS, JavaScript). No build step, no dependencies.

shahd-portfolio/
  index.html        all content
  css/styles.css    design tokens at the top (colors, fonts)
  js/script.js      mobile menu, active nav link, scroll reveal
  assets/images/    optimized images from the PowerPoint

## Run locally
Double-click index.html, or run a local server:
  python -m http.server 8000     (then open http://localhost:8000)

## Deploy free
- Netlify: https://app.netlify.com/drop  -> drag the shahd-portfolio folder.
- GitHub Pages: push the folder contents to a repo, Settings > Pages > Deploy from branch (main, / root).
- Cloudflare Pages: connect the repo, leave build command empty, output directory "/".
