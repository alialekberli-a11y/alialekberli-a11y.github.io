# Bonovira Marketing Site

This repository contains the static marketing website for Bonovira.

## Publishing to GitHub Pages

1. Fork or clone this repository to your GitHub account.
2. Commit any customizations you make locally.
3. Push the `main` branch to your GitHub repository.
4. In your repository settings, enable **GitHub Pages** for the `main` branch (or `docs/` folder if you move the files).
5. Your site will be available at `https://<your-username>.github.io/<repository-name>/`.

If you already have the files locally and only need to update your GitHub repository, stage the changes, commit with a descriptive message, and push to `main`:

```bash
git add .
git commit -m "Update marketing site"
git push origin main
```

## Local preview

Open `index.html` directly in your browser, or run a lightweight HTTP server:

```bash
python3 -m http.server
```

Then visit [http://localhost:8000](http://localhost:8000) to preview the site.

## Structure

- `index.html` – landing page overview of Bonovira's platform.
- `solutions.html` – detailed view of solutions and platform capabilities.
- `about.html` – company story, leadership, and service model.
- `styles.css` – shared stylesheet applied across pages.
- `sample-report.pdf` – downloadable example insights report.
- `logo.png`, `dispenser.png`, `Bonovira dashboard.png` – brand and product imagery used across the site.

Feel free to customize the copy, imagery, or structure to match your brand voice before publishing.
