# Academic Website

A clean, static academic website with sections for Home, Bio, News, Research Interests, and Publications.

## Edit Your Content

Most personal content lives in `index.html`.

- Replace `Your Name`, title, department, location, and contact links.
- Update the Bio paragraphs.
- Add or remove entries in the scrollable News section.
- Replace the research interests and publication placeholders.

Design styles live in `styles.css`, and the small mobile menu / active navigation behavior lives in `script.js`.

## Preview Locally

Because this is a static site, you can open `index.html` directly in a browser.

You can also run a tiny local server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish on GitHub Pages

Option 1: publish from the main branch.

1. Create a new GitHub repository, for example `academic-website`.
2. Push this folder to GitHub.
3. In the repository settings, go to Pages.
4. Set the source to `Deploy from a branch`.
5. Select the `main` branch and `/root` folder.

Option 2: use the included GitHub Actions workflow.

1. Push this folder to GitHub.
2. In repository settings, go to Pages.
3. Set the source to `GitHub Actions`.
4. Pushes to `main` will deploy automatically.

## Suggested Repository Name

For a personal site at `https://USERNAME.github.io`, name the repository:

```text
USERNAME.github.io
```

For a project-style site, any repository name is fine.
