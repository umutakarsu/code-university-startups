# Setup Instructions

## Quick Start

This project is ready to use! Here's how to get started:

### 1. Move Project to Desired Location

The project is currently in your Claude workspace. To move it to `/Users/umutakarsu/code-university-website`:

```bash
# Option A: Copy the entire folder
cp -r "code-university-website" ~/code-university-website

# Option B: Move the entire folder
mv "code-university-website" ~/code-university-website
```

### 2. Complete Git Setup

The git repository has been initialized. To complete the setup with your first commit:

```bash
cd ~/code-university-website

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit: CODE University startups showcase website

- Add responsive HTML showcase page for CODE University student startups
- Include comprehensive README with setup instructions
- Add .gitignore for common development environments
- Feature 6 notable startups: SLAY, Kombo, Langdock, Certus One, AULIOS, Bool Capital"

# Verify everything is committed
git status
```

### 3. Open in Code (VS Code or similar)

```bash
cd ~/code-university-website
code .
```

Or simply drag the folder into your code editor.

### 4. View the Website

Open `index.html` in your browser:

```bash
# macOS
open index.html

# Or start a local server
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## What's Included

- ✅ `index.html` - Beautiful, responsive showcase website
- ✅ `README.md` - Comprehensive project documentation
- ✅ `.gitignore` - Configured for common development environments
- ✅ Git repository initialized (commit pending)

## Optional: Add Remote Repository

If you want to push this to GitHub, GitLab, or similar:

```bash
# Create a new repository on GitHub/GitLab first, then:
git remote add origin https://github.com/yourusername/code-university-website.git
git branch -M main
git push -u origin main
```

## Optional Enhancements

### Add a Build Process

If you want to add optimization, minification, or preprocessing:

```bash
npm init -y
npm install --save-dev vite

# Add to package.json:
# "scripts": {
#   "dev": "vite",
#   "build": "vite build",
#   "preview": "vite preview"
# }
```

### Add GitHub Pages Deployment

1. Push to GitHub
2. Go to Settings → Pages
3. Select main branch as source
4. Your site will be live at `https://yourusername.github.io/code-university-website`

### Add Custom Domain

Create a `CNAME` file with your domain:

```bash
echo "code-startups.yourdomain.com" > CNAME
git add CNAME
git commit -m "Add custom domain"
```

## Troubleshooting

**Q: The website doesn't display correctly**
- Make sure you're opening `index.html` directly or via a web server
- Check browser console for any errors

**Q: Git commands fail**
- Make sure you're in the project directory
- Verify git is installed: `git --version`

**Q: Want to make changes?**
- Edit `index.html` directly
- All styles are in the `<style>` section
- No build process needed for basic changes

## Support

For questions about CODE University, visit [code.berlin](https://code.berlin)

---

**Ready to code!** 🚀
