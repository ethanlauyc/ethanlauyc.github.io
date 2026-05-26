# Quick Start Guide 🚀

## What You Have

A complete, production-ready GitHub Pages portfolio template with:
- Professional HTML structure
- Modern, responsive CSS styling
- Interactive JavaScript features
- Jekyll configuration
- Ready for deployment

## Next Steps

### Step 1: Initialize Git Repository

Open Terminal/PowerShell in your project folder and run:

```bash
git init
git add .
git commit -m "Initial portfolio template"
```

### Step 2: Create GitHub Repository

1. Go to [github.com](https://github.com) and log in
2. Click **New repository**
3. Name it `your-username.github.io` (recommended) or any name
4. Make it **Public**
5. Click **Create repository**

### Step 3: Push to GitHub

Run these commands:

```bash
git remote add origin https://github.com/your-username/your-repo-name.git
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select **main** branch and **/ (root)** folder
4. Click **Save**

### Step 5: Wait for Deployment

GitHub will build your site (usually takes 1-2 minutes).

Your portfolio is now live at:
- `https://your-username.github.io` (if repo is `username.github.io`)
- `https://your-username.github.io/repo-name` (if different repo name)

## Files to Customize Now

1. **index.html** - Update:
   - "Your Name" → Your actual name
   - "your.email@example.com" → Your email
   - Project descriptions
   - Social links

2. **_config.yml** - Update:
   - title
   - description
   - url
   - author

3. **assets/css/style.css** - Customize colors in `:root` section

## Local Testing (Optional)

To preview before deploying:

```bash
# Install Jekyll (requires Ruby)
gem install bundler jekyll

# Run local server
jekyll serve

# Visit http://localhost:4000
```

## Common Issues

### Changes not showing up?
- Wait 2-5 minutes for GitHub to rebuild
- Hard refresh your browser (Ctrl+Shift+R or Cmd+Shift+R)
- Check GitHub Actions in your repo for build errors

### Can't find your site?
- Check repository is Public
- Verify GitHub Pages is enabled in Settings → Pages
- Ensure branch is set to `main` (or your default branch)

## Support Resources

- [GitHub Pages Docs](https://docs.github.com/en/pages)
- [Jekyll Docs](https://jekyllrb.com/)
- Check `README.md` for detailed customization guide

---

**You're all set! Happy coding! 💻**
