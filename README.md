# Sample portfolio site (Git and GitHub for Your Career, Lab 5)

A one-page portfolio in plain HTML and CSS, ready for GitHub Pages. No build step, no framework.

| File | What to change |
|---|---|
| `index.html` | Your name, tagline, what you are looking for, your projects, skills, about text and contact links |
| `style.css` | Colours at the top (`--navy`, `--cyan`); the rest can stay |
| `images/avatar.svg` | Replace with your photo (`images/avatar.jpg`, square) and update the two `avatar.svg` references |
| `images/*.png`, `*.jpg` | One screenshot per project, about 1200 x 680 px, under 300 KB |
| `resume.pdf` | Optional: add your résumé as a PDF (without your home address or phone number) and un-comment its link in `index.html` |
| `.nojekyll` | Leave it: it tells GitHub Pages to publish the files as they are |

Preview it on your computer before you push:

```bash
python -m http.server 8000      # in this folder; then open http://localhost:8000 (Ctrl+C to stop)
```

Publish it: create a public repository named exactly `YOUR-USERNAME.github.io`, push these files to its `main`
branch, then Settings → Pages → Build and deployment → Source: *Deploy from a branch*, Branch: `main`, folder `/ (root)`.
After a minute or two the site is at `https://YOUR-USERNAME.github.io`.

Alex Rivera, Example University and the three projects are made-up examples (Weather Stats is the starter project
of Lab 4). Replace them, and the pictures, with your own work.
