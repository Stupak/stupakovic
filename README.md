# stupakovic-portfolio

Personal portfolio site for Viacheslav Stupak — Senior UX Architect.

## Structure

```
stupakovic-portfolio/
├── index.html                 # Homepage
├── project-go.html            # ProjectGO case study
├── gendocs-ai.html            # GenDocs AI case study
├── intelligent-testing.html   # Intelligent Testing case study
└── assets/
    ├── cv/
    │   └── cv_stupak_2026.pdf
    └── images/
        ├── project-go/
        ├── gendocs-ai/
        └── intelligent-testing/
```

## Preview locally

From this folder, run:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080 in your browser.

## Next steps

1. Add project screenshots to the matching `assets/images/*` folders
2. Replace image placeholders in case study pages with `<img src="assets/images/...">` tags
3. Deploy to GitHub Pages, Netlify, or your domain (e.g. stupakovic.com)

## Deploy (GitHub Pages)

```bash
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin YOUR_REPO_URL
git push -u origin main
```

Enable GitHub Pages in repo Settings → Pages → deploy from `main` branch root.
