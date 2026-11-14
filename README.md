# Portfolio

Personal portfolio of Gnanojval. One static `index.html`, no build step, deployed with GitHub Pages.

- A single message up top (backend systems and ML tooling, measured), then three lanes matching the kind of role a visitor is hiring for: backend systems, ML you can measure, testing and validation.
- Nine projects as an expandable table: what was built, how it works, the measured numbers, and what's still rough.
- LeetCode stats (Knight, rating, global top %) with baked-in defaults that refresh live from a public API.
- Light and dark themes (follows the system, toggle in the header).

## Editing

Projects are plain `<details class="row">` blocks inside the three `.lane` sections of `index.html`. The resume link is the `RESUME_URL` constant at the top of the script.
