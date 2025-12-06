# Cancer Awareness & Support — Single-file Website

This is a small, responsive single-file website for the internship assignment.
Files included:
- `index.html` — the full site (landing, contact form, quotes widget)

## How to use locally
1. Save `index.html` and open it in your browser.
2. No server/backend required. The contact form simulates submission client-side.
3. Quotes are fetched from `https://api.quotable.io/random` (public API).

## Deploy to GitHub Pages
1. Create a new GitHub repo and push `index.html` to the repository root or to a `docs/` folder.
2. In GitHub repo settings → Pages, choose branch `main` and folder `/ (root)` or `/docs` depending where you put the file.
3. GitHub will provide a URL like `https://<username>.github.io/<repo>/` within a minute or two.

## Deploy to Netlify
1. Create a new site → drag & drop the `index.html` file onto Netlify, or connect your GitHub repo.
2. Netlify will host it and give you a live URL immediately.

## Deploy to Vercel
1. Create a new Vercel project and import the repo or drag the file to the dashboard.
2. Vercel will auto-deploy and provide a URL.

## Customize
- Replace the hero banner image by editing the `<img src=\"...\">` in the `.hero-banner` element.
- To capture form submissions in production, use Formspree, Netlify Forms, or a simple server endpoint.

## Notes
- The file is intentionally simple and self-contained for easy hosting.
- If you'd like I can: provide a zipped package, deploy it to Netlify/GitHub Pages for you, or add analytics/meta tags.
