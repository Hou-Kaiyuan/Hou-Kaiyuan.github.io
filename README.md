# hou-kaiyuan.github.io

Personal academic website of Kaiyuan Hou — <https://hou-kaiyuan.github.io>

Built with [Jekyll](https://jekyllrb.com/) on the
[AcademicPages](https://github.com/academicpages/academicpages.github.io) theme (a fork of
[Minimal Mistakes](https://mademistakes.com/work/minimal-mistakes-jekyll-theme/)), deployed by GitHub Pages
from the `master` branch.

## Structure

| Path | Contents |
| --- | --- |
| `_pages/about.md` | Home page: bio, news, education, experience, awards |
| `_pages/publications.md` | Research page: selected projects and full publication list |
| `_pages/teaching.html` | Teaching and mentoring overview |
| `_pages/cv.md` | CV page (links and embeds the PDF in `files/`) |
| `_teaching/` | One file per course taught |
| `_data/navigation.yml` | Top navigation |
| `_sass/_custom.scss` | Site-specific styles (news list, project cards, publication list) |
| `images/publications/` | Project teaser figures and clips |
| `files/` | CV PDFs |

## Common updates

- **New paper**: add an entry to the `Publications` list in `_pages/publications.md`; if it deserves a
  teaser, add a card under `Selected Projects` and drop the figure in `images/publications/`.
- **News item**: add an `<li>` at the top of the `.news` list in `_pages/about.md`.
- **New CV**: add the PDF to `files/` and update the two links plus the date in `_pages/cv.md`.

Keep teaser figures under ~250 KB (resize to ~1400 px wide, JPEG). Convert animated GIFs to MP4 —
a looping `<video autoplay loop muted playsinline>` is an order of magnitude smaller.

## Local preview

```bash
bundle install
bundle exec jekyll serve   # http://127.0.0.1:4000
```
