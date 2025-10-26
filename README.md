# Nurse Lead Care Agency — Website

This repository contains a React + Tailwind CSS website template for **Nurse Lead Care Agency**.
It is ready to be built and deployed to GitHub Pages or any static hosting provider.

## Quick start

1. Install dependencies
```bash
npm install
```

2. Run development server
```bash
npm run dev
```

3. Build for production
```bash
npm run build
```

4. Serve a preview locally
```bash
npm run preview
```

## Deploy to GitHub Pages (simple steps)

Option A — Deploy `dist/` manually:
- Run `npm run build` to create the production `dist/` folder.
- Create a new branch `gh-pages`, copy the contents of `dist/` into the branch root, commit and push, then in the GitHub repository settings enable GitHub Pages to serve from `gh-pages` branch (root).

Option B — Use an action or the `peaceiris/actions-gh-pages` action to publish the `dist/` directory automatically on push to `main` (search GitHub Actions for "deploy Vite to GitHub Pages").

## Custom domain
If you want to use a custom domain (e.g. `nurseleadcare.co.uk`):
1. Create or update a `CNAME` file containing your domain name in the `gh-pages` branch (or put it into `dist/` before publishing).
2. Configure your domain DNS to point to GitHub Pages (use GitHub docs for exact A/CNAME records).
3. Enable the custom domain in the repository's Pages settings.

---
**Note:** The Apply form in this template simulates a file upload and shows a "Thank you" message inline. To receive uploads via email or database, integrate a backend or a form service (Formspree, Netlify Forms, etc.).
