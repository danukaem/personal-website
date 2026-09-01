# danukaem.github.io/personal-website

Personal website of **Danuka Malawana** — Full Stack Developer, Sri Lanka.

A single-page static site: one hand-written `index.html` with inline CSS and vanilla JavaScript.
No build step, no framework, no jQuery or Bootstrap.

## Structure

```
index.html        the whole site (markup + styles + script)
assets/           images
.nojekyll         serve files as-is on GitHub Pages
robots.txt, sitemap.xml
```

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

GitHub Pages serves the `master` branch root. Push to `master` and the site updates in a minute or two.

Settings → Pages → Source: *Deploy from a branch* → Branch: `master` / `/ (root)`.

## Editing

- Text, experience, projects and education all live directly in `index.html` under their `<section>` tags.
- Colours and spacing are CSS variables at the top of the `<style>` block (`--accent`, `--bg`, `--radius`, …).
