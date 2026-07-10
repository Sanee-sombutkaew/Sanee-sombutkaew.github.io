# Sanee Sombutkaew — portfolio site

Plain HTML/CSS/JS. No build step, no framework.

## Files
- `index.html` — home page: resume (bio, experience, skills, education, contact)
- `data-analysis.html` — Data Analysis Projects page (placeholder, content pending)
- `operations-planning.html` — Operations & Planning Projects page (placeholder, content pending)
- `style.css` — all styling, shared across every page
- `script.js` — mobile menu toggle, shared across every page

All three pages share the same nav bar, so visitors can move between Resume,
Data Analysis, and Operations & Planning from anywhere on the site.

## Publish with GitHub Pages
1. Create a new repo on GitHub named exactly: `Sanee-sombutkaew.github.io`
2. Upload all five files (`index.html`, `data-analysis.html`,
   `operations-planning.html`, `style.css`, `script.js`) to the repo root
   (drag-and-drop on github.com works, or use GitHub Desktop / git push)
3. Go to repo Settings → Pages → under "Build and deployment", set Source to
   "Deploy from a branch", branch `main`, folder `/ (root)` → Save
4. Within a minute, your site is live at:
   https://sanee-sombutkaew.github.io

## To update later
- Edit `index.html` for resume content changes (text, links, new job entries)
- Edit `data-analysis.html` and `operations-planning.html` to swap the
  "Projects coming soon" placeholder panel for real project write-ups
- Edit `style.css` for colors, spacing, fonts (shared by every page)
- Commit and push (or re-upload the changed file on github.com) — the live
  site rebuilds automatically within about a minute, no other steps needed

## To add images (e.g. a profile photo)
1. Create a folder called `images/` in the repo
2. Add your photo, e.g. `images/profile.jpg`
3. In `index.html`, replace the placeholder avatar circle in the hero section
   with: `<img src="images/profile.jpg" alt="Sanee Sombutkaew">`
