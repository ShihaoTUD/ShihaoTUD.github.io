# Deployment Instructions for GitHub Pages

## Files Created
- index.html (Home page)
- research.html (Research page)
- publications.html (Publications page)
- news.html (News page)
- gallery.html (Gallery page)

## How to Deploy to GitHub Pages

### Method 1: Using GitHub Web Interface
1. Go to your GitHub repository: https://github.com/shihaotud/shihaotud.github.io
2. Click "Add file" → "Upload files"
3. Upload all 5 HTML files (index.html, research.html, publications.html, news.html, gallery.html)
4. Click "Commit changes"
5. Wait 1-2 minutes for GitHub Pages to rebuild
6. Visit: https://shihaotud.github.io

### Method 2: Using Git Command Line
```bash
# Navigate to your local repository
cd path/to/shihaotud.github.io

# Copy the HTML files to your repository
# (Download them from the outputs folder first)

# Add all files
git add .

# Commit the changes
git commit -m "Update website with new pages"

# Push to GitHub
git push origin main
```

## File Structure
Your repository should look like this:
```
shihaotud.github.io/
├── index.html
├── research.html
├── publications.html
├── news.html
├── gallery.html
└── CV_Shihao_Fu.pdf (optional)
```

## Troubleshooting
- If pages show 404 error, make sure all files are in the root directory of your repository
- File names are case-sensitive
- Wait 1-2 minutes after pushing for changes to appear
- Clear your browser cache if you don't see updates

## Next Steps
1. Upload your photo and replace the commented-out image tag in index.html
2. Upload your CV PDF as "CV_Shihao_Fu.pdf"
3. Update social media links with your actual profile URLs
4. Add research images to the gallery page
