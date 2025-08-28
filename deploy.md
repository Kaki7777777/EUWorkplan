# Quick Deployment Guide

## Option 1: GitHub Pages (Recommended)

1. **Upload to GitHub:**
   ```bash
   git add github-pages/cngs-gtm-contributions/
   git commit -m "Add CNGS GTM contributions presentation"
   git push origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click Settings > Pages
   - Source: "Deploy from a branch"
   - Branch: "main"
   - Folder: "/github-pages/cngs-gtm-contributions"
   - Click Save

3. **Access your presentation:**
   - URL will be: `https://[your-username].github.io/HiQ/github-pages/cngs-gtm-contributions/`
   - GitHub will provide the exact URL in the Pages settings

## Option 2: Direct File Sharing

Simply share the `index.html` file - it's completely self-contained and will work when opened in any browser.

## Option 3: Local Development Server

If you have Python installed:
```bash
cd github-pages/cngs-gtm-contributions/
python -m http.server 8000
```
Then open: http://localhost:8000

## Updating Content

1. Edit `index.html`
2. Test locally by opening in browser
3. Push changes to GitHub (if using GitHub Pages)
4. Changes will be live within a few minutes

## Sharing

Once deployed, you can share the GitHub Pages URL with:
- Helen (for 9/16 review)
- Jiaqi (for 9/25 review)
- Other stakeholders for alignment discussions
