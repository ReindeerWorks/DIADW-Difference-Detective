# 🚀 Quick Setup Guide for GitHub

## Step 1: Create a New Repository

1. Go to [GitHub.com](https://github.com) and log in
2. Click the "+" in the top right → "New repository"
3. Name it: `different-detective` (or whatever you prefer)
4. Make it **Public**
5. Don't initialize with README (we have one)
6. Click "Create repository"

## Step 2: Upload Your Files

### Option A: Via GitHub Website (Easiest)
1. On your new repo page, click "uploading an existing file"
2. Drag and drop these 4 files:
   - `index.html`
   - `image1.png`
   - `image2.png`
   - `README.md`
3. Add commit message: "Initial commit - Different Detective game"
4. Click "Commit changes"

### Option B: Via Command Line
```bash
cd path/to/different-detective
git init
git add .
git commit -m "Initial commit - Different Detective game"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/different-detective.git
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. In your repository, click "Settings" tab
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click "Save"
5. Wait 2-3 minutes for deployment

## Step 4: Get Your Live URL

Your game will be live at:
```
https://YOUR-USERNAME.github.io/different-detective/
```

For example, if your username is `nicksmith`:
```
https://nicksmith.github.io/different-detective/
```

## 🎉 That's It!

Share your link and let people play!

## 🔧 Making Updates

To update the game after changes:

**Via GitHub Website:**
1. Click on the file you want to edit
2. Click the pencil icon (Edit)
3. Make your changes
4. Commit changes at the bottom

**Via Command Line:**
```bash
git add .
git commit -m "Update game"
git push
```

Changes will be live in 2-3 minutes!

## 💡 Pro Tips

1. **Custom Domain**: You can use a custom domain in Pages settings
2. **Analytics**: Add Google Analytics to track plays
3. **Social Sharing**: Add Open Graph meta tags for better link previews
4. **Multiple Scenes**: Create different HTML files for different scenes

## 🐛 Troubleshooting

**Game not loading?**
- Make sure all 4 files are in the root directory
- Check that images are named exactly `image1.png` and `image2.png`
- Try accessing with `/index.html` at the end of the URL

**Images not appearing?**
- Verify image files uploaded correctly
- Check browser console (F12) for errors
- Make sure image names match exactly in the HTML

## 📧 Need Help?

If you run into issues, check:
1. GitHub Pages is enabled in settings
2. Repository is public (or you have GitHub Pro for private Pages)
3. All files are in the root directory
4. Wait 2-3 minutes after any changes
