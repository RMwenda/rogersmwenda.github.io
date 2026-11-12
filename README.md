# Rogers Mwenda: personal profile site

A plain HTML, CSS and JavaScript site. No build step and no dependencies.

## Files

| File | What it controls |
| --- | --- |
| `index.html` | All the text and sections. Search for `EDIT:` to find the spots to change first. |
| `style.css` | Colours (the `:root` block at the top), fonts, spacing, dark mode. |
| `script.js` | Closes the "More" menu after a click. Nothing else. |
| `assets/headshot.jpg` | Optional photo. When present, it replaces the RM monogram. |

## Publish on GitHub Pages

1. Create a **public** repository named exactly `YOUR-USERNAME.github.io` (your GitHub username, lowercase).
2. Upload everything in this folder to the repository root (`index.html` must sit at the top level). Include the hidden `.nojekyll` file.
3. Go to **Settings > Pages**. Under "Build and deployment", choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. Wait a minute or two. Your site goes live at `https://YOUR-USERNAME.github.io/`.

Command line version:

```bash
git init
git add .
git commit -m "Initial profile site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
git push -u origin main
```

## Edit later

Change a file, commit, push (or use the pencil icon on GitHub). The site refreshes within a couple of minutes.

## Change the colours

At the top of `style.css`, `--brand: #164E45;` is the main green. The dark-mode values are in the two `prefers-color-scheme` and `data-theme="dark"` blocks just below it.
