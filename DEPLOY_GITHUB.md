# PORTILAME ANCHOR Framework — GitHub Pages Deployment

## Quick Setup (5 minutes)

### 1. Create a new GitHub repository

Go to https://github.com/new and create a new repository:
- Name: `anchor-framework` (or whatever you prefer)
- Set to **Private** (the password on the site already protects the content)
- Do NOT initialize with README

### 2. Upload the site files

Option A — Via GitHub web interface (simplest):
1. Open your new repo on GitHub
2. Click "Add file" → "Upload files"
3. Drag the entire contents of the `site/` folder:
   - `index.html`
   - `ANCHOR_Presentation.pptx`
4. Click "Commit changes"

Option B — Via terminal:
```bash
cd /path/to/site
git init
git add .
git commit -m "PORTILAME ANCHOR Framework"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/anchor-framework.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under "Source", select **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)**
4. Click **Save**
5. Wait 1-2 minutes for deployment

### 4. Access your site

Your site will be live at:
```
https://YOUR_USERNAME.github.io/anchor-framework/
```

Password: `anchor2026`

## Notes

- The PPTX download link works automatically (it's in the same directory as index.html)
- If you use a private repo, GitHub Pages requires a GitHub Pro/Team/Enterprise plan
- Alternative: use a public repo — the content is password-protected anyway
- To update: simply replace the files and push again
