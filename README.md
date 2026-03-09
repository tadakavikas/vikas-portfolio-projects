# vikas-portfolio-projects

Software Engineer | Data Analyst | Python • SQL • JavaScript • Data Visualization

## Run locally

Start a local static server from the project root and open http://localhost:8000:

```bash
python3 -m http.server 8000
```

## Deploy with GitHub Pages

1. Create a Git repository and push to GitHub (replace `YOURUSERNAME` and `REPO`):

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/YOURUSERNAME/REPO.git
git push -u origin main
```

2. On GitHub, go to the repository Settings → Pages and set the source to the `main` branch (root) or enable GitHub Actions deployment.

3. After enabling, your site will be available at `https://YOURUSERNAME.github.io/REPO`.

If you want, I can create a GitHub Actions workflow to automatically build/deploy to `gh-pages` for you.
