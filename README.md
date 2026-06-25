# Abdul Basit Ustad — Portfolio Site

A simple static portfolio website (HTML/CSS, no build step needed).

## Files
- `index.html` — the page content
- `style.css` — all styling
- `assets/` — images (hero background, project placeholder image)

## How to publish on GitHub Pages

1. **Create a new repository** on GitHub, e.g. `portfolio` (or `yourusername.github.io` if you want it at the root domain).

2. **Upload these files** to the repo, keeping the same folder structure:
   ```
   index.html
   style.css
   assets/
     hero-bg.png
     bridge-bg.jpg
   ```
   You can do this via the GitHub web UI ("Add file → Upload files") or with git:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repo → Settings → Pages
   - Under "Build and deployment", set Source = "Deploy from a branch"
   - Branch = `main`, folder = `/ (root)`
   - Save

4. Your site will be live in a minute or two at:
   - `https://<your-username>.github.io/<repo-name>/` (normal repo), or
   - `https://<your-username>.github.io/` (if the repo is named `<your-username>.github.io`)

## Updating later
- Replace the placeholder project card in `index.html` (search for `[ 04 / SELECTED WORKS ]`) once you have project content ready — just duplicate the `.project-card` block for each new project.
- Swap images in `assets/` any time — just keep the same filenames, or update the `background-image` paths in `index.html`.
