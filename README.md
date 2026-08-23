# Faisal Akhtar — Portfolio (Massively / HTML5 UP)

Your content, combined with the exact matching version of the "Massively"
HTML5 UP template (the one using `browser.min.js` + `breakpoints.min.js`,
same as your original `index.html` expects — no swapped-out files this time).

## What's in this folder

```
faisal-site-v2/
├── index.html
├── LICENSE.txt                    ← HTML5 UP's license (keep it — required by their terms)
├── original-template-README.txt   ← template credits, for reference
├── assets/
│   ├── css/main.css
│   ├── css/noscript.css
│   ├── css/fontawesome-all.min.css
│   ├── webfonts/                   ← Font Awesome icon font files
│   └── js/
│       ├── jquery.min.js
│       ├── jquery.scrollex.min.js
│       ├── jquery.scrolly.min.js
│       ├── browser.min.js
│       ├── breakpoints.min.js
│       ├── util.js
│       └── main.js
└── images/                         ← YOUR PROJECT SCREENSHOTS GO HERE
```

## ⚠️ Before you publish

**1. Replace the placeholder dashboard images.** Drop your real exported
screenshots into `images/`, using these exact filenames (matching what
`index.html` already references — odd repeated dots included, so you don't
have to edit any code):

- `superstore power bi dashboard.png`
- `superstore power bi dashboard..png`
- `superstore power bi dashboard...png`
- `pizza sales power bi dashboard.png`
- `pizza sales power bi dashboard..png`
- `power bi HR Dashboard.png`
- `E-commerce Analytics Dashboard.png`

**2. Fix a GitHub link mismatch.** Your file has `github.com/faisalakhtar` in
the nav icons but `github.com/faisalakhtar007` in the footer contact section —
pick the correct one and make both consistent (search for "faisalakhtar" in
`index.html` to find both spots).

## How to publish on GitHub Pages

1. Create a free account at [github.com](https://github.com) if needed.
2. Create a repo named exactly `your-username.github.io` (your real username)
   — gives you the URL `https://your-username.github.io`.
3. From inside this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
   git push -u origin main
   ```
4. GitHub → **Settings → Pages** → Source: "Deploy from a branch" → branch
   `main`, folder `/ (root)` → **Save**.
5. Wait 1–2 minutes → visit `https://your-username.github.io`.

Future edits: `git add . && git commit -m "..." && git push`.

## Local preview

Double-click `index.html` — it now has full styling and icon fonts.
