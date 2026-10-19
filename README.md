# Purple Mind website

Marketing site for Purple Mind, a marketing agency for online therapy and telehealth practices.

## Files
- `index.html`: the landing page
- `quiz.html`: the Practice Growth Assessment
- `start.html`: landing page for Instagram ads (link ads to `/start`)
- `netlify.toml`: Netlify settings (publish folder and security headers)
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

## Forms
Both forms use Netlify Forms, so they only collect submissions on the Netlify site (not on GitHub Pages).
- `instagram-audit`: the form on `start.html`
- `assessment`: the quiz results form on `quiz.html`

In Netlify, turn on form detection (Forms tab) and add an email under Notifications → Form submission notifications.
