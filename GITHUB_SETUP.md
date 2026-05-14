# GitHub Setup Guide

Follow these steps to host your CBS course materials on GitHub Pages.

## Prerequisites

- GitHub account (free at [github.com](https://github.com))
- Git installed on your computer ([git-scm.com](https://git-scm.com))
- Your course HTML files ready to upload

## Step 1: Create a New Repository

1. Go to [github.com/new](https://github.com/new)
2. Enter repository name: `cbs-course` (or your preferred name)
3. Add description: "AI, Fintech & Deep Tech course materials — CBS Summer 2026"
4. Choose **Public** (so it's accessible to everyone)
5. ✅ Check "Add a README file"
6. Click **Create repository**

## Step 2: Initialize Your Local Repository

If you're starting fresh on your computer:

```bash
# Create a folder for your project
mkdir cbs-course
cd cbs-course

# Initialize git
git init

# Add your files (copy them to this directory first):
# - index.html
# - CBS_W1_Day1.html
# - CBS_W1_S3_Data_Governance.html
# - CBS_W1_S4_Quantum.html
# - CBS_W1_S5_Synthesis.html
# - README.md
# - LICENSE
# - .gitignore
# - .github/workflows/pages.yml

# Stage all files
git add .

# Commit
git commit -m "Initial commit: CBS course materials"

# Add remote (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/cbs-course.git

# Push to GitHub (this will prompt for authentication)
git branch -M main
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (right side menu)
3. In the left sidebar, click **Pages**
4. Under "Build and deployment":
   - Source: Select **Deploy from a branch**
   - Branch: Select **main**
   - Folder: Select **/ (root)**
5. Click **Save**

GitHub will automatically deploy within 1-2 minutes.

## Step 4: Access Your Site

Once deployment is complete:

- **Your site URL:** `https://YOUR_USERNAME.github.io/cbs-course`
- Check the **Actions** tab to see deployment status
- A green checkmark means it's live!

## Step 5: Update Your Files

To make changes later:

```bash
# Edit your files locally
# Then sync with GitHub:

git add .
git commit -m "Update: Add Week 2 sessions"
git push

# Your site updates automatically within 1-2 minutes
```

## Common Git Commands

```bash
# Check status
git status

# View recent commits
git log --oneline

# Undo last commit (before pushing)
git reset --soft HEAD~1

# Pull latest changes (if editing on GitHub)
git pull origin main
```

## Troubleshooting

### "GitHub Pages is not enabled"
- Wait 2-3 minutes after enabling in Settings
- Refresh the page
- Check the Actions tab for any errors

### "Site not loading"
- Ensure `index.html` is in the root folder
- Check that all file names match exactly (case-sensitive)
- Verify internet connection (CDN resources need to load)

### "Want to use a custom domain?"
In Settings → Pages, you can add a custom domain:
- `yourdomain.com`
- Requires DNS configuration (detailed guides available)

### "Need help with Git?"
- [GitHub Desktop](https://desktop.github.com) — Visual GUI for Git
- [Git basics](https://git-scm.com/doc) — Official documentation
- [GitHub Docs](https://docs.github.com) — Comprehensive guides

## File Checklist

Before pushing, ensure you have:

- ✅ `index.html` — Main landing page
- ✅ `CBS_W1_Day1.html` — Week 1 Day 1 slides
- ✅ `CBS_W1_S3_Data_Governance.html` — Session 3 slides
- ✅ `CBS_W1_S4_Quantum.html` — Session 4 slides
- ✅ `CBS_W1_S5_Synthesis.html` — Session 5 slides
- ✅ `README.md` — Documentation
- ✅ `LICENSE` — MIT License
- ✅ `.gitignore` — Git ignore rules
- ✅ `.github/workflows/pages.yml` — Auto-deployment config

## Optional: Add a Badge to Your README

Show off your GitHub Pages deployment:

```markdown
[![GitHub Pages](https://img.shields.io/badge/hosted%20on-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://YOUR_USERNAME.github.io/cbs-course)
```

## Next Steps

1. ✅ Create the repository
2. ✅ Push your files
3. ✅ Enable GitHub Pages
4. ✅ Share the link with students: `https://YOUR_USERNAME.github.io/cbs-course`
5. ✅ Update as new weeks become available

---

**Need Help?**
- GitHub Support: [support.github.com](https://support.github.com)
- Community: [GitHub Discussions](https://github.com/community/community)
- Stack Overflow: Tag with `github-pages` and `github`
