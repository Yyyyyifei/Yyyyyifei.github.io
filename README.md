# Yifei Sun

Personal academic website for Yifei Sun, built as a lightweight static site and hosted with GitHub Pages.

Live site:

```text
https://Yyyyyifei.github.io
```

## Overview

This site presents my academic profile, research interests, recent updates, and publications. It is intentionally simple: plain HTML, CSS, and JavaScript, with no build step or package manager required.

## Structure

```text
.
├── index.html                  # Page content and section structure
├── styles.css                  # Visual design and responsive layout
├── script.js                   # Mobile navigation and active section state
├── prof_pic.jpg                # Profile photo
├── .nojekyll                   # Keeps GitHub Pages from applying Jekyll processing
└── .github/workflows/pages.yml # GitHub Pages deployment workflow
```

## Local Preview

Open `index.html` directly in a browser, or run a small local server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Editing

Most content updates happen in `index.html`:

- Update the biography and contact links in the Home section.
- Add news items under the `#news` section.
- Add publications under the `#publications` section.
- Edit research interests under the `#research` section.

Design changes belong in `styles.css`. The only JavaScript behavior is the responsive navigation in `script.js`.

## Deployment

The site deploys through GitHub Actions whenever changes are pushed to `main`.

GitHub Pages settings:

```text
Settings -> Pages -> Build and deployment -> Source -> GitHub Actions
```

To publish updates:

```bash
git add .
git commit -m "Update website"
git push
```

## Notes

This repository is configured as a user GitHub Pages site. The repository name should remain:

```text
Yyyyyifei.github.io
```
