# 🚀 GitHub Pages Deployment Guide for PhoneHub

This comprehensive guide will walk you through deploying the PhoneHub website to GitHub Pages in just a few steps.

## Prerequisites

Before you start, make sure you have:
- ✅ A GitHub account (free at github.com)
- ✅ Git installed on your computer
- ✅ All PhoneHub files ready (you have them!)

## If You Don't Have Git Installed

### For Windows:
1. Download Git from: https://git-scm.com/download/win
2. Run the installer
3. Accept default options
4. Restart your computer
5. Open Command Prompt or PowerShell and verify: `git --version`

### For Mac:
1. Download Git from: https://git-scm.com/download/mac
2. Or use Homebrew: `brew install git`
3. Verify: `git --version`

### For Linux:
```bash
# Ubuntu/Debian
sudo apt-get install git

# Fedora
sudo dnf install git

# Verify
git --version
```

## Step-by-Step Deployment

### Step 1: Create a GitHub Repository

1. Go to https://github.com and log in to your account
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Fill in the details:
   - Repository name: `phonehub` (or any name you like)
   - Description: "Online Phone Sales Website" (optional)
   - Choose "Public" (so it can be accessed via GitHub Pages)
   - ✅ Check "Add a README file" or you can skip (we have one)
5. Click "Create repository"

### Step 2: Initialize Local Repository and Push Code

Open Command Prompt or Terminal and navigate to your PhoneHub directory:

```bash
cd "c:\Users\HP\OneDrive\Desktop\Website Design & Development\CODE_WED"
```

Then run these commands one by one:

```bash
# Initialize git in your project directory
git init

# Configure your git identity (one-time setup)
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Add all files to git
git add .

# Create your first commit
git commit -m "Initial commit: PhoneHub e-commerce website with 6 pages and localStorage integration"

# Rename branch to main (GitHub's default)
git branch -M main

# Add the remote repository URL (replace 'yourusername' with your actual GitHub username)
git remote add origin https://github.com/yourusername/phonehub.git

# Push your code to GitHub
git push -u origin main
```

**Important:** In the last two commands, replace `yourusername` with your actual GitHub username!

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub (https://github.com/yourusername/phonehub)
2. Click the "Settings" gear icon at the top right
3. Click "Pages" in the left sidebar
4. Under "Source", select the dropdown currently showing "None"
5. Choose "main" branch
6. Click "Save"
7. GitHub will show you the URL where your site is published!

### Step 4: Access Your Live Website

Your website will be live at:
```
https://yourusername.github.io/phonehub/
```

**Note:** It may take a few minutes (up to 5-10 minutes) for GitHub to deploy your site.

## Making Updates to Your Site

After the initial deployment, if you make changes to your files:

```bash
# Make your changes to the HTML/CSS/JS files

# Stage the changes
git add .

# Commit with a descriptive message
git commit -m "Update: Added new features to checkout page"

# Push to GitHub
git push origin main
```

Your site will automatically update within a few moments!

## Troubleshooting

### Issue: "fatal: not a git repository"
**Solution:** Make sure you're in the correct directory and have run `git init`

### Issue: "remote origin already exists"
**Solution:** Use this to update the URL:
```bash
git remote set-url origin https://github.com/yourusername/phonehub.git
```

### Issue: Changes aren't showing on the website
**Solution:** 
- Wait 5-10 minutes for GitHub to rebuild the site
- Clear your browser cache (Ctrl+F5 or Cmd+Shift+R)
- Check the Pages settings in repository Settings

### Issue: "refused to merge unrelated histories"
**Solution:**
```bash
git pull origin main --allow-unrelated-histories
git commit -m "Merge remote and local"
git push origin main
```

### Issue: 404 Page Not Found
**Ensure:**
- Your repository is PUBLIC (not private)
- GitHub Pages is enabled in Settings > Pages
- index.html is in the root directory (not in a subdirectory)

## Custom Domain (Optional)

If you want to use a custom domain:

1. Go to your domain registrar (GoDaddy, Namecheap, etc.)
2. Point your domain to GitHub Pages using these DNS records:
   - A records: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - For subdomains: Create CNAME pointing to yourusername.github.io
3. In GitHub Settings > Pages, enter your custom domain
4. GitHub will automatically create a CNAME file

## Useful Git Commands

```bash
# Check git status
git status

# View commit history
git log

# See changes made
git diff

# Undo changes to a file
git checkout -- filename.html

# Remove a file from git
git rm filename

# View all remote repositories
git remote -v
```

## Security Note

⚠️ **Important:** Never commit sensitive information like:
- Passwords
- API keys
- Private credentials

The .gitignore file already excludes common sensitive files.

## Resources

- Git documentation: https://git-scm.com/doc
- GitHub Pages docs: https://docs.github.com/en/pages
- GitHub Guides: https://guides.github.com

## Next Steps

After deployment, consider:

1. **Sharing Your Project**
   - Share the live URL with friends and colleagues
   - Include it in your portfolio
   - Show it to potential employers

2. **Enhancements**
   - Add more phone models
   - Implement a backend API
   - Add user email notifications
   - Connect a real payment gateway

3. **Learning**
   - Study the code structure
   - Modify styles and layouts
   - Add more JavaScript features
   - Build upon this foundation

## Success! 🎉

If your site is now live at https://yourusername.github.io/phonehub/, congratulations! You've successfully deployed your first web project!

---

**Questions?** Check the troubleshooting section or refer to:
- GitHub Pages Documentation: https://docs.github.com/en/pages
- Git Documentation: https://git-scm.com/doc

**Happy deploying!** 🚀
