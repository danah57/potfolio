# Portfolio Deployment Guide

## Option 1: GitHub Pages (FREE & EASY)

### Steps:
1. **Create GitHub Repository:**
   - Go to [github.com](https://github.com)
   - Click "New repository"
   - Name it: `danah-portfolio`
   - Make it Public
   - Click "Create repository"

2. **Upload Files:**
   - Upload these files to your repository:
     - `ai_engineer_portfolio_single_file_website_ready_to_deploy.html` (rename to `index.html`)
     - `styles.css`
     - `Danah CV.pdf`
     - `photos/` folder (with all images)

3. **Enable GitHub Pages:**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Source: "Deploy from a branch"
   - Branch: "main"
   - Folder: "/ (root)"
   - Click "Save"

4. **Your Portfolio URL:**
   - `https://danah57.github.io/danah-portfolio`

---

## Option 2: Netlify (FREE & EASY)

### Steps:
1. **Go to [netlify.com](https://netlify.com)**
2. **Sign up with GitHub**
3. **Drag & Drop:**
   - Create a folder with all your files
   - Drag the folder to Netlify
4. **Your Portfolio URL:**
   - `https://random-name.netlify.app`

---

## Option 3: Vercel (FREE & EASY)

### Steps:
1. **Go to [vercel.com](https://vercel.com)**
2. **Sign up with GitHub**
3. **Import your repository**
4. **Deploy automatically**

---

## Option 4: Firebase Hosting (FREE)

### Steps:
1. **Install Firebase CLI:**
   ```bash
   npm install -g firebase-tools
   ```

2. **Initialize Firebase:**
   ```bash
   firebase init hosting
   ```

3. **Deploy:**
   ```bash
   firebase deploy
   ```

---

## Quick Fix for File Paths

Make sure your HTML file uses relative paths:
- ✅ `./photos/photo2.jpg`
- ✅ `./styles.css`
- ✅ `./Danah CV.pdf`

---

## Recommended: GitHub Pages

**Why GitHub Pages?**
- ✅ Completely FREE
- ✅ Easy to update
- ✅ Professional URL
- ✅ Fast loading
- ✅ No ads

**Your final URL will be:**
`https://danah57.github.io/danah-portfolio`

---

## After Deployment

1. **Test all links** - Make sure GitHub links work
2. **Test on mobile** - Check responsive design
3. **Share your URL** - Add to LinkedIn, CV, etc.

---

## Need Help?

If you need help with any step, let me know!
