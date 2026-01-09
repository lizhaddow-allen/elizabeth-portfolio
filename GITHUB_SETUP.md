# GitHub Pages Setup Guide

Follow these steps to get your portfolio website live on GitHub Pages.

## Step 1: Create a GitHub Account
1. Go to https://github.com
2. Click "Sign up" (if you don't have an account)
3. Follow the registration process

## Step 2: Create a New Repository
1. Click the "+" icon in the top right corner
2. Select "New repository"
3. Name your repository: `elizabeth-portfolio` (or any name you prefer)
4. Set it to **Public**
5. DO NOT initialize with README (we already have files)
6. Click "Create repository"

## Step 3: Upload Your Files
You have two options:

### Option A: Upload via Web Interface (Easiest)
1. On your new repository page, click "uploading an existing file"
2. Drag and drop these files:
   - `index.html`
   - `README.md`
   - `.gitignore`
3. Add a commit message like "Initial commit - portfolio website"
4. Click "Commit changes"

### Option B: Using Git Command Line
```bash
git init
git add .
git commit -m "Initial commit - portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/elizabeth-portfolio.git
git push -u origin main
```

## Step 4: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on **Settings** (top menu)
3. Scroll down and click **Pages** (left sidebar)
4. Under "Source", select:
   - Branch: **main**
   - Folder: **/ (root)**
5. Click **Save**
6. Wait 2-5 minutes for deployment

## Step 5: Access Your Live Site
Your website will be available at:
```
https://YOUR-USERNAME.github.io/elizabeth-portfolio/
```

**Example**: If your GitHub username is "elizabethha", your site will be:
```
https://elizabethha.github.io/elizabeth-portfolio/
```

## Step 6: Share Your Link
Once live, you can share this URL with anyone! The site is:
- ✅ Publicly accessible
- ✅ Mobile-responsive
- ✅ Professional and polished
- ✅ No hosting costs

## Updating Your Site
To make changes:
1. Edit `index.html` locally
2. Go to your GitHub repository
3. Click on `index.html`
4. Click the pencil icon (Edit)
5. Make your changes
6. Scroll down and click "Commit changes"
7. Changes will be live in 1-2 minutes

## Using a Custom Domain (Optional)
If you want to use a custom domain like `elizabethhaddowallen.com`:
1. Purchase domain from Namecheap, GoDaddy, etc.
2. In GitHub Pages settings, add your custom domain
3. Configure DNS records (GitHub provides instructions)

## Troubleshooting

**Site not loading?**
- Wait 5-10 minutes after enabling Pages
- Check that your main file is named `index.html`
- Ensure repository is set to Public

**Changes not showing?**
- Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
- Wait 2-3 minutes for GitHub to rebuild
- Clear browser cache

**Need help?**
- GitHub Pages Documentation: https://docs.github.com/en/pages
- GitHub Support: https://support.github.com/

---

## Quick Checklist
- [ ] GitHub account created
- [ ] New repository created (`elizabeth-portfolio`)
- [ ] Files uploaded (`index.html`, `README.md`, `.gitignore`)
- [ ] GitHub Pages enabled in Settings
- [ ] Site is live and accessible
- [ ] Link tested and shared

**Congratulations!** Your professional portfolio is now live on the internet! 🎉
