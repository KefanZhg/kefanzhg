# kefanzhg personal site

Personal website for GitHub Pages.

## Files

- `index.html` — main page content
- `styles.css` — page styles

## Deploy to GitHub Pages

1. Create a public repository named `kefanzhg.github.io`.
2. Upload all files in this folder to the repository root.
3. Go to **Settings → Pages** in GitHub.
4. Set:
   - **Source**: Deploy from a branch
   - **Branch**: `main` / `(root)`
5. Save and wait 1–2 minutes.
6. Open: `https://kefanzhg.github.io`

## Update content

- Edit text/content sections in `index.html`
- Edit colors/layout in `styles.css`

## Local preview

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open:

- http://localhost:8000

Stop the server with `Ctrl+C`.

## FAQ

### Should I put the personal webpage in `README.md`?

No. GitHub Pages renders website files like `index.html`, not `README.md`.

- `index.html` = your actual website page
- `README.md` = repository documentation shown on the repo page

### My site doesn’t update immediately. Why?

GitHub Pages deployment can take a minute or two. Refresh after a short wait.

## Source profile

- LinkedIn: https://www.linkedin.com/in/kefan-zheng-8299891ba/

## Pre-publish checklist

- [ ] Email link works (`mailto:kefanzhg@gmail.com`)
- [ ] LinkedIn and GitHub links open correctly
- [ ] Work Experience dates/titles are accurate
- [ ] Top 3 projects appear first in Project Experience
- [ ] Tech Stack lines are visible for each project card
- [ ] Mobile layout looks good (`< 640px` width)
- [ ] No placeholder text remains in `index.html`
- [ ] GitHub Pages is enabled on `main` / `(root)`
