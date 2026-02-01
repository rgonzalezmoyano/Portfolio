# Quarto portfolio (Spotify-style, research focused)

This is a starter Quarto website meant for a Research Scientist intern application (causal inference + ML).

## 1) Edit the placeholders
Search for:
- <YOUR_GITHUB_USERNAME>
- <REPO_NAME>
- <YOUR_EMAIL>
- <YOUR_GITHUB_URL>
- <YOUR_LINKEDIN_URL>

Also place your CV at `assets/cv.pdf`.

## 2) Render locally
```bash
quarto render
```

This project is configured to output to `docs/` so it can be published with GitHub Pages (main branch, /docs).

## 3) Publish with GitHub Pages (docs method)
1. Push the repo to GitHub
2. In your repo: **Settings → Pages**
3. Source: **Deploy from a branch**
4. Branch: `main` and folder `/docs`

Commit `docs/` after rendering:
```bash
git add docs
git commit -m "Publish site"
git push
```

## Optional: GitHub Actions
If you prefer CI builds, follow Quarto's official GitHub Pages Action guide and add a workflow.
See: https://quarto.org/docs/publishing/github-pages.html
