# Your Portfolio Site — Getting Started

This folder has everything you need:
- `index.html` — Home page: hero, About, Contact
- `projects.html` — Projects page
- `certifications.html` — Certifications page
- `awards.html` — Awards & Achievements page
- `skills.html` — Skills page
- `styles.css` — all the visual styling, shared by every page
- `script.js` — the small bit of code that makes the mobile menu work, shared by every page

Every page has the same nav bar at the top. Clicking "About" or "Contact"
from any page takes you back to `index.html` and scrolls to that section.
Clicking "Projects," "Certifications," "Awards," or "Skills" opens that
page directly — all within the same browser tab, since these are your
own pages, not external sites.

## Step 1 — Open it in VS Code

1. Install VS Code: https://code.visualstudio.com (free)
2. Open VS Code → **File > Open Folder** → select this `portfolio` folder
3. Install the **"Live Server"** extension (search for it in the Extensions
   panel — the icon that looks like four squares, on the left sidebar)
4. Right-click `index.html` in the file list → **"Open with Live Server"**
   This opens your site in a browser and auto-refreshes every time you save.

## Step 2 — Make it yours

Replace the placeholder text in each file:
- `index.html` — your name, the hero role line, the About paragraph and facts list, contact links at the bottom
- `projects.html` — each project card (title, description, role, tools, link)
- `certifications.html` — each certification (name, issuer, date, verify link)
- `awards.html` — each award/achievement (year, title, context)
- `skills.html` — your tool/skill groups

The nav bar and footer are repeated at the top and bottom of every file
— if you change your name, email, or social links, update it in all
five files (`index.html`, `projects.html`, `certifications.html`,
`awards.html`, `skills.html`) so they stay consistent.

You don't need to touch `styles.css` or `script.js` unless you want to
change colors, fonts, or spacing later — those are shared by every page.

## Step 3 — Put it on GitHub Pages (free hosting)

1. Create a free account at https://github.com if you don't have one
2. Click the **+** in the top right → **New repository**
   - Name it something like `portfolio`
   - Keep it Public
   - Don't add a README (you already have one)
3. On the new repo's page, click **"uploading an existing file"**
   and drag in `index.html`, `projects.html`, `certifications.html`,
   `awards.html`, `skills.html`, `styles.css`, and `script.js`
   → Commit the changes
4. Go to the repo's **Settings** tab → **Pages** (left sidebar)
   - Under "Source," choose the `main` branch and `/ (root)` folder → Save
5. Wait about a minute, then refresh that Pages settings tab — it will
   show your live link, something like:
   `https://yourusername.github.io/portfolio/`

That link is now your live, shareable portfolio site. Any time you want
to update it, edit the files and re-upload them (or ask me — this can
also be done straight from VS Code once you're comfortable with Git).

## Later, optional upgrades
- A custom domain (e.g. yourname.com) — can be pointed at GitHub Pages for ~$10–15/year
- Swapping the placeholder Google Fonts for something else
- Adding real project images/screenshots
