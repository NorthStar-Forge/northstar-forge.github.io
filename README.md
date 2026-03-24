# northstar-forge.github.io

Public site for **NorthStar Forge** at [https://northstar-forge.github.io/](https://northstar-forge.github.io/).

## One-time GitHub setup

1. **Create the GitHub account or organization** with handle **`northstar-forge`** (required for this exact URL).  
   If the name is taken, pick another handle; your site URL will be `https://<that-handle>.github.io/`.

2. On GitHub, create a **new public repository** named exactly **`northstar-forge.github.io`** (under the `northstar-forge` account).

3. **Push this folder** (from your machine):

   ```bash
   cd /path/to/northstar-forge.github.io
   git init
   git branch -M main
   git add .
   git commit -m "Initial NorthStar Forge site"
   git remote add origin https://github.com/northstar-forge/northstar-forge.github.io.git
   git push -u origin main
   ```

4. **Enable Pages**: Repository → **Settings** → **Pages** → Build and deployment → Source: **Deploy from a branch** → Branch **`main`** → folder **`/ (root)`** → Save.

5. Wait a few minutes, then open **https://northstar-forge.github.io/**

## Updating the site

Edit files in this repo, commit, and push to `main`. Pages rebuilds automatically.

## Syncing design tokens from your personal portfolio

This site vendors copies of `portfolio-base.css`, `reptrack.css`, and `js` from your personal Pages repo. After you change those files there, copy them here again if you want the studio site to match.
