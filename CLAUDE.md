# Purple Mind website

Marketing site for Purple Mind, an agency for online therapy and telehealth practices. It is a plain static site with no build step: `index.html` (landing page), `quiz.html` (8-question Practice Growth Assessment) and `shared.css` (shared colors, fonts and buttons).

- Hosting: GitHub Pages from `main`. Live at https://sathviklagadapati-coder.github.io/purple-mind-website/
- GitHub CLI: `~/.local/bin/gh` (not on PATH), logged in as `sathviklagadapati-coder`.
- Open work and decisions: see `NEXT-STEPS.md` (booking setup is paused there).
- Design rules: purple is a small accent only (primary buttons, one headline phrase, progress lines, the selected quiz answer, the score ring). Everything else is neutral charcoal or grey. The "pm." logo keeps plum #221236 and lavender #D8C3FB. Both light and dark themes are supported. Check changes at phone width (375px).
- Content rules: no client testimonials, no made-up stats or results, keep the 988 crisis line in the footer.
- Preview locally: `python3 -m http.server 8765`
