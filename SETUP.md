# Setup and publishing

All animated SVG images and decorative badges are intentionally non-clickable. They are rendered as images, not links. Do not wrap any `<img>` or badge Markdown in a link (`[![...](image)](URL)`). Keep normal text links in the README only if you want clickable text.

Before publishing:
1. Replace portrait placeholders with transparent PNGs.
2. Confirm/remove technology labels and add a real description for `pass`.
3. Add your permanent Discord invite if desired.
4. Upload `README.md` and the complete `assets/` folder to the root of public repo `ambanigaming0`.
5. Commit and inspect desktop/mobile rendering.


## Prevent SVG image click-through
The README wraps each SVG image in `<a href="#">...</a>` so a click stays on the profile page instead of opening the raw SVG. GitHub strips arbitrary CSS/JavaScript, so a truly disabled pointer event is not available in README Markdown. The separate social badges remain clickable.


## Prevent image clicks
In the local `preview.html`, `pointer-events:none` disables clicking the SVG artwork. GitHub sanitizes/controls README rendering, so a README cannot reliably disable the platform's native click-to-open image behaviour. Use the explicit labeled badges below the artwork for navigation. Avoid wrapping SVG `<img>` tags in links if you do not want them to act as links.
