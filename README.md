# oliviams.com — website files

## Structure
- `index.html` — home page
- `publications.html` — publications list
- `cv.html` — CV / experience
- `talks.html` — talks & presentations
- `teaching.html` — teaching history
- `_style.css` — shared stylesheet
- `files/cv.pdf` — your CV PDF (add this yourself)
- `CNAME` — custom domain (already set to oliviams.com)

## Deploying to GitHub Pages

1. Copy all these files into your `oliviams.github.io` repository (replacing the existing files)
2. Add your CV PDF as `files/cv.pdf`
3. Commit and push — the site will go live at oliviams.com within minutes

## Updating content

- **New publication**: add a `<div class="pub-item">` block in `publications.html`
- **News item**: add a `<div class="news-item">` block in `index.html`
- **New talk**: add a `<div class="item">` block in `talks.html`

## Custom domain
The `CNAME` file is already configured for `oliviams.com`.
Make sure your GitHub Pages settings (Settings → Pages → Custom domain) also shows `oliviams.com`.
