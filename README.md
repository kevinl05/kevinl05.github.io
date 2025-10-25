# Portfolio Site

A clean, modern portfolio to showcase AI projects.

## Local Development

Just open `index.html` in your browser to see it.

## Deploying to GitHub Pages

1. **Create a GitHub repository** named `yourusername.github.io` (replace `yourusername` with your actual GitHub username)

2. **Initialize git and push:**
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click Settings → Pages
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click Save

4. **Your site will be live at:** `https://yourusername.github.io`

It usually takes a few minutes for the site to go live after the first push.

## Updating

Just edit `index.html`, commit, and push:
```bash
git add .
git commit -m "Update portfolio"
git push
```

Changes will be live in a few minutes.
