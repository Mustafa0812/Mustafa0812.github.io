# Portfolio site

Static site: `index.html` (all CSS inline) plus images in `assets/img/`. No build step.

## Publish on GitHub Pages

1. Create a public repo named `Mustafa0812.github.io`.
2. Push the contents of this folder to its `main` branch.
3. The site goes live at `https://mustafa0812.github.io` within a minute or two.

## Updating

- Text: edit `index.html`. Each project is an `<article class="project">` block.
- Images: add WebP/JPEG files to `assets/img/` (about 1000–1600 px wide is plenty).
- Flight controller renders were exported from the KiCad board file with:
  `kicad-cli pcb render --rotate "-35,0,30" --quality high -o fc.png FlightController.kicad_pcb`
