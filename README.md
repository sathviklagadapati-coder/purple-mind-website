# Purple Mind website

Marketing site for Purple Mind, a marketing agency for online therapy and telehealth practices.

## Files
- `index.html`: the landing page
- `quiz.html`: the Practice Growth Assessment
- `shared.css`: colors, fonts and buttons shared by both pages

It is a static site with no build step and nothing to install.

## Preview locally
```bash
python3 -m http.server 8765
```
Then open http://localhost:8765

## Deploy
It currently deploys automatically to GitHub Pages whenever `main` is pushed:
https://sathviklagadapati-coder.github.io/purple-mind-website/

The site is plain HTML and CSS, so any static host can serve it as-is:
- **Custom domain on GitHub Pages:** add the domain under Settings → Pages, then point your DNS at GitHub.
- **Netlify, Vercel or Cloudflare Pages:** import this GitHub repo, leave the build command empty and set the output folder to the repo root.

## Before launch
Neither form sends anything yet. See `NEXT-STEPS.md`.
