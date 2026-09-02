# molinqin.com

Personal academic website of Molin Qin. A single static HTML page with no build step.

## Structure

| Path | Purpose |
| --- | --- |
| `index.html` | The entire site: intro, education, research, teaching |
| `css/style.css` | Styling. Light/dark follows the visitor's system preference |
| `files/Molin_Qin_CV.pdf` | CV linked from the nav bar and intro |
| `images/` | Portrait and favicons |
| `404.html` | Not-found page |
| `CNAME` | Custom domain for GitHub Pages |

## Editing

- **Add a paper**: copy one `<article class="paper">` block in `index.html` and edit the title, coauthors, venue, links, and abstract. Abstracts use a `<details>` element, so they are collapsed by default.
- **Update the CV**: replace `files/Molin_Qin_CV.pdf`.
- **Change the photo**: replace `images/phd2.jpg`.
- **Bump the footer date** at the bottom of `index.html`.

Preview locally by opening `index.html` in a browser, or run `python -m http.server` in this folder and visit `http://localhost:8000`.
