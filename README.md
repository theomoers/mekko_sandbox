# CKI Emissions Mekko (GitHub Pages)

This repository is configured to publish the dashboard as a static site.

## Included in publish

- `index.html` (entry point)
- `mekko_modern_with_tech.html` (dashboard)
- `template/emissions_from_ngfs_btco2e.csv`
- `template/technology_overlay.csv`
- `template/BAU_emissions.csv`

All other files in this folder are ignored by `.gitignore` by default.

## Deploy to GitHub Pages

1. Create a new GitHub repository (empty, no README/license).
2. From this folder:

```bash
git init -b main
git add .
git commit -m "Publish CKI emissions dashboard"
git remote add origin <YOUR_GITHUB_REPO_URL>
git push -u origin main
```

3. In GitHub:
   - Go to `Settings` -> `Pages`
   - `Build and deployment` -> `Source`: `Deploy from a branch`
   - Branch: `main` and folder `/ (root)`

4. Open the published URL:
   - `https://<your-username>.github.io/<repo-name>/`

