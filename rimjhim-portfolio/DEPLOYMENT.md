# GitHub Deployment Guide

## Quick Start - Push to GitHub

### Step 1: Create GitHub Repository
1. Go to [github.com](https://github.com) and log in
2. Click "+" icon → "New repository"
3. Name it: `rimjhim-portfolio`
4. Choose "Public" (so it's accessible via GitHub Pages)
5. Click "Create repository"

### Step 2: Connect Local Repository to GitHub
Copy the HTTPS URL from your newly created repository, then run:

```bash
cd c:/Users/Admin/Downloads/task1/rimjhim-portfolio
git remote add origin https://github.com/YOUR_USERNAME/rimjhim-portfolio.git
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitHub username.

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" (top right)
3. Click "Pages" in the left sidebar
4. Under "Build and deployment":
   - Source: Select "Deploy from a branch"
   - Branch: Select "main" and "/root"
   - Click "Save"

### Step 4: Your Portfolio is Live!
Wait 1-2 minutes, then visit:
```
https://YOUR_USERNAME.github.io/rimjhim-portfolio/
```

## Updating Your Portfolio

After making changes:

```bash
cd c:/Users/Admin/Downloads/task1/rimjhim-portfolio
git add .
git commit -m "Update portfolio: [describe your changes]"
git push origin main
```

Changes will be live within seconds!

## Customization Checklist

- [ ] Add your profile image to `public/profile.jpg`
- [ ] Update contact email in index.html
- [ ] Add social media links (LinkedIn, GitHub, etc.)
- [ ] Update project descriptions
- [ ] Update skills percentages
- [ ] Change color scheme if desired (edit Tailwind classes)

## Troubleshooting

**Pages not showing?**
- Wait 2-3 minutes after enabling GitHub Pages
- Check repository is public
- Verify branch is set to "main" in Pages settings

**Image not loading?**
- Make sure `profile.jpg` is in the `public/` folder
- Try clearing browser cache (Ctrl+Shift+R)

---

Need help? Check out [GitHub Pages Documentation](https://docs.github.com/en/pages)
