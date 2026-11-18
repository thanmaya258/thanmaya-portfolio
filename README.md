# Thanmaya Rishi Portfolio

A plain HTML, CSS and JavaScript portfolio. No build step, no dependencies.

## Files

- `index.html`, `style.css`, `script.js`
- `assets/favicon.svg`
- `assets/pomodoro.png` and `assets/kitten-cafe.png` (add these yourself, screenshots of each project)

## Publish on GitHub Pages

1. Sign in to GitHub as `thanmaya258`.
2. Click **New repository**. Name it exactly `thanmaya258.github.io`, set it to **Public**, and create it.
3. Add the files. Either drag and drop everything (including the `assets` folder) using **Add file > Upload files**, or run:
   ```
   git init
   git add .
   git commit -m "Add portfolio"
   git branch -M main
   git remote add origin https://github.com/thanmaya258/thanmaya258.github.io.git
   git push -u origin main
   ```
4. Open the repository **Settings > Pages**.
5. Under **Build and deployment**, set Source to **Deploy from a branch**, choose branch `main` and folder `/ (root)`, then click **Save**.
6. Wait one or two minutes, then visit https://thanmaya258.github.io.

## Before you publish

- Add `assets/pomodoro.png` and `assets/kitten-cafe.png`.
- Check the Kitten Cafe "Source Code" link in `index.html` and point it to the real repository.
- Keep personal details such as school, town, email, phone and photos off the site.

## Updating

Edit a file, commit and push. The site refreshes within a minute or two.
