# borisayala.com

Personal site for Boris Ayala, built with [Jekyll](https://jekyllrb.com/).

Every push to `master` runs `.github/workflows/deploy.yml`, which builds the site and publishes `_site` to the `gh-pages` branch. GitHub Pages serves that branch at www.borisayala.com.

## Editing

- Page content: `index.html`, `research.html`, `cv.html`, `teaching.html`, `contact.html`
- Courses on the Teaching page: `_data/courses.yml` (syllabus PDFs go in `assets/pdf/syllabi/`)
- Shared header, nav and footer: `_layouts/default.html`
- Styles: `assets/css/site.css`
- Nav items: `nav` in `_config.yml`

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
