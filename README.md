# Calvo Lab website

Static website of the Calvo Lab (Department of Systems Biology, CNB-CSIC, Madrid; opening 2027), served with GitHub Pages.

- `index.html` is the whole site; the cartoons are drawn inline as SVG.
- `assets/` holds the images, videos, favicon, and the free fallback font (Source Serif 4, SIL Open Font License).
- `.nojekyll` tells GitHub Pages to serve the files as they are.

To update a text, edit `index.html` on github.com (pencil icon) and commit; the live site refreshes within a minute or two.

Titles are designed for Canela Text Bold. Without a web-font license, visitors see Source Serif 4; to switch, add the licensed `.woff2` file to `assets/fonts/` and reference it in the `"Canela Site"` `@font-face` rule at the top of `index.html`.

Images and videos: Calvo Lab and collaborators. Figures adapted from published papers are credited in the Highlights section.
