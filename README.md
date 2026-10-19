# Swapnil Rajendra Bodade — Portfolio

A responsive, dark-theme professional portfolio for GitHub Pages. Built with plain HTML, CSS, and JavaScript; no build tools or dependencies are required.

## Before publishing

Search `index.html` for starter copy and replace it with accurate information from your CV:
- About: your actual professional summary.
- Skills: only technologies and methods you have used.
- Projects: actual projects, outcomes, and repository links. Current cards are prompts, not claims of completed work.
- Experience and education: actual employers, dates, roles, qualifications, and institutions.
- Contact: add a professional email if you want it public.

The CV button expects a file named `resume.pdf` in the repository root. Add your own PDF with that filename, or change the link in `index.html`. Do not publish a CV containing personal information you do not want to make public.

## Publish with GitHub Pages

### Recommended: use the repository root

1. Sign in to GitHub and open https://github.com/swapnil358/
2. Create a **new public repository** named exactly `swapnil358.github.io` (if that repository does not already exist). A user-site repository must match the GitHub username.
3. Upload `index.html`, `style.css`, `script.js`, and this `README.md` to the repository's root. Add `resume.pdf` after replacing the placeholder CV link with your real file.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then click **Save**.
7. Wait for the Pages deployment to complete. The site should be available at `https://swapnil358.github.io/`.

If `swapnil358.github.io` already exists, use that repository rather than creating a duplicate. Alternatively, create another repository and enable Pages from its `main` branch root; its URL will be `https://swapnil358.github.io/REPOSITORY-NAME/`. For a project site, relative links like `style.css` and `resume.pdf` work with this setup.

## Local preview

Open `index.html` in a browser. For a more realistic local preview, run a simple static server from this folder, for example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Files

- `index.html` — page content and sections
- `style.css` — responsive layout and theme
- `script.js` — mobile navigation and current footer year
- `resume.pdf` — add your own CV PDF here (not included)

## Notes

- No contact form is included, so there is no nonfunctional form to mislead visitors.
- Social profile links point to the GitHub and LinkedIn URLs supplied for this site.
- Google Fonts are loaded from Google's CDN; the site otherwise works without a build process.
