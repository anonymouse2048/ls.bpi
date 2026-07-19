# Lapburn Spanaxeess (site)

This repository contains a small static site. If the root URL returns a 404, make sure `index.html` exists at the repository root and is pushed to the `main` branch.

Quick commands to push your local changes (run in the project folder):

```bash
git add index.html login.html secret.html README.md
git commit -m "Add index redirect and README"
git branch -M main
git remote add origin https://github.com/yourusername/ls.bpi.git
git push -u origin main
```

Then open the repository `Settings → Pages` and set the source to `main` / root.

If you already have `origin` configured, skip the `git remote add` line.
