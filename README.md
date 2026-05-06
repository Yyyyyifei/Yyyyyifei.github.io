# Yifei Sun Academic Website

A polished static academic website with sections for Home, Publications, Research, News, and Bio.

## Edit Your Content

Most personal content lives in `index.html`.

- Update the opening bio, affiliation, location, and contact links.
- Add or remove entries in the News section.
- Add publications in the ordered list under `#publications`.
- Replace `prof_pic.jpg` if you want a different profile photo.

Design styles live in `styles.css`, and the small mobile menu / active navigation behavior lives in `script.js`.

## Preview Locally

Because this is a static site, you can open `index.html` directly in a browser.

You can also run a tiny local server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish on GitHub Pages

### Option 1: GitHub Actions

1. Create a new GitHub repository, for example `academic-website`.
2. Push this folder to the repository.
3. In the repository settings, go to **Pages**.
4. Under **Build and deployment**, set **Source** to **GitHub Actions**.
5. Pushes to `main` will deploy automatically using `.github/workflows/pages.yml`.

### Option 2: Deploy From Branch

1. Push this folder to GitHub.
2. In the repository settings, go to **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select the `main` branch and `/root` folder.
5. Save, then wait for GitHub Pages to publish the site.

## First Push Commands

From this folder:

```bash
git init
git add .
git commit -m "Publish academic website"
git branch -M main
git remote add origin https://github.com/USERNAME/REPOSITORY.git
git push -u origin main
```

## Suggested Repository Name

For a personal site at `https://USERNAME.github.io`, name the repository:

```text
USERNAME.github.io
```

For a project-style site, any repository name is fine.
