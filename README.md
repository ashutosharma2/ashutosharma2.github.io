# ashutosharma2.github.io

My portfolio: a one-page site with sticky-note cards for experience, projects and certifications.

Live at **https://ashutosharma2.github.io**

## What's here

| File | Contents |
|---|---|
| `index.html` | The whole site: markup, styles and a small script, with no build step |
| `hero.jpg` | Photo in the hero frame |
| `favicon.svg` | Cloud logo for the browser tab |
| `Ashutosh_Sharma_Resume.pdf` | Résumé linked from the hero and contact sections |

## Editing

Experience, projects and certifications are lists at the top of the `<script>` in `index.html` (`WORK`, `PROJECTS`, `CERTS`). Edit an entry there and the notes and project spec sheets update to match. Everything else is plain HTML.

To preview locally:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploying

GitHub Pages serves the `main` branch. Push to `main` and the site updates within a minute or two.
