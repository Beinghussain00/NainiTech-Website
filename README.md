## README.md

```markdown
# Multipage Website — Final Assignment

**Purpose:** A responsive, multipage website to showcase a small business/portfolio with contact form, navigation, responsive layout, and interactive elements.

**Pages:** Home (index.html), About (about.html), Services (services.html), Contact (contact.html).

## How to use
1. Copy the files into a folder called `multipage-site`.
2. Open `index.html` in your browser to preview locally.
3. Optionally host using GitHub Pages / Netlify / Vercel (instructions below).

## Deployment
### GitHub Pages
1. Create a GitHub repository and push the `multipage-site` directory.
2. In repository Settings -> Pages, choose branch `main` (root) and save.
3. Visit the provided `https://<username>.github.io/<repo>/` URL.

### Netlify
1. Create a Netlify account and connect your GitHub repository.
2. Set build settings to `build command: none`, `publish directory: /` (for static sites).
3. Deploy; Netlify will provide a live URL.

### Vercel
1. Create a Vercel account and import the GitHub repo.
2. No build step required for static HTML; deploy and copy the URL.

## Notes & best practices
- Keep assets under `images/` and use relative paths.
- Validate HTML/CSS using online validators.
- Add `rel="noopener noreferrer"` to external links.
- Add meta viewport and accessible ARIA attributes where appropriate.
