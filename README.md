# Ilan Strauss - Personal Website

Academic portfolio site built for GitHub Pages.

## Quick Deploy to GitHub Pages (FREE)

### Step 1: Create the Repository

1. Go to [github.com/new](https://github.com/new)
2. Name it exactly: `IlanStrauss.github.io` (must match your username)
3. Make it **Public**
4. Click "Create repository"

### Step 2: Upload Files

Option A - Via GitHub web interface:
1. Click "uploading an existing file"
2. Drag all files from this folder
3. Click "Commit changes"

Option B - Via command line:
```bash
cd /Users/ilanstrauss/personal-website-github
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/IlanStrauss/IlanStrauss.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to repository Settings → Pages
2. Under "Source", select `main` branch
3. Click Save

Your site will be live at: **https://ilanstrauss.github.io**

## Files

- `index.html` - Homepage with current projects and works in progress
- `research.html` - Published papers and articles
- `about.html` - Background, education, affiliations
- `style.css` - Clean academic styling
- `assets/img/` - Put your headshot here as `headshot.jpg`
- `assets/docs/` - Put your CV PDF here as `cv.pdf`

## To Do Before Deploying

1. **Add a headshot**: Save a professional photo as `assets/img/headshot.jpg`
2. **Add your CV**: Save your CV PDF as `assets/docs/cv.pdf`
3. **Review and update** any information on the pages

## Customization

The site uses simple HTML and CSS - easy to modify:
- Colors are defined as CSS variables at the top of `style.css`
- Content is plain HTML - just edit the text
- Add new papers by copying the `paper-entry` div structure

## Custom Domain (Optional - ~$10-15/year)

If you want a custom domain like `ilanstrauss.com`:

1. Buy domain from Namecheap, Cloudflare, or Google Domains
2. In GitHub repo: Settings → Pages → Custom domain
3. Add DNS records as instructed
4. Create a `CNAME` file with your domain name
