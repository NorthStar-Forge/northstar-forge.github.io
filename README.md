# northstar-forge.github.io

Public site for **NorthStar Forge** at [https://northstar-forge.github.io/](https://northstar-forge.github.io/).

## One-time GitHub setup

1. **Create a GitHub organization** whose **login** resolves to the hostname you want. This project uses org **`NorthStar-Forge`** on GitHub; the public site URL is still **`https://northstar-forge.github.io/`** (GitHub lowercases the Pages hostname).

2. On GitHub, create a **new public repository** named exactly **`northstar-forge.github.io`** under that org (already done for NorthStar Forge).

3. **Push this folder** (from your machine):

   ```bash
   cd /path/to/northstar-forge.github.io
   git init
   git branch -M main
   git add .
   git commit -m "Initial NorthStar Forge site"
   git remote add origin https://github.com/NorthStar-Forge/northstar-forge.github.io.git
   git push -u origin main
   ```

4. **Enable Pages**: Repository → **Settings** → **Pages** → Build and deployment → Source: **Deploy from a branch** → Branch **`main`** → folder **`/ (root)`** → Save.

5. Wait a few minutes, then open **https://northstar-forge.github.io/**

## Updating the site

Edit files in this repo, commit, and push to `main`. Pages rebuilds automatically.

## Syncing design tokens from your personal portfolio

This site vendors copies of `portfolio-base.css`, `reptrack.css`, and `js` from your personal Pages repo. After you change those files there, copy them here again if you want the studio site to match.
