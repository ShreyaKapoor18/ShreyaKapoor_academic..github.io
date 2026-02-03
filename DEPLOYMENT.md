# 🚀 Deployment Guide

## Step-by-Step Instructions to Deploy Your Website

### Prerequisites
- GitHub account
- Git installed on your computer
- Your profile photo ready (400x400px recommended)

---

## Method 1: Fresh GitHub Repository (Recommended)

### 1. Create a New Repository on GitHub

1. Go to [GitHub](https://github.com) and log in
2. Click the **"+"** icon in the top right → **"New repository"**
3. **Repository name**: `YourUsername.github.io` 
   - Replace `YourUsername` with your actual GitHub username
   - Example: `ShreyaKapoor18.github.io`
4. Set to **Public**
5. **Do NOT** initialize with README, .gitignore, or license
6. Click **"Create repository"**

### 2. Upload Your Files

**Option A: Using Git (Command Line)**

```bash
# Navigate to the folder containing your website files
cd path/to/github-site

# Initialize git repository
git init

# Add all files
git add .

# Commit the files
git commit -m "Initial commit - Portfolio website"

# Add your GitHub repository as remote
# Replace YOUR_USERNAME with your GitHub username
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**Option B: Using GitHub Web Interface**

1. On your new repository page, click **"uploading an existing file"**
2. Drag and drop all your website files
3. Click **"Commit changes"**

### 3. Add Your Profile Photo

1. Navigate to the `images` folder in your repository
2. Upload your profile photo and name it **exactly** `profile.png`
3. Commit the change

### 4. Enable GitHub Pages

1. Go to your repository **Settings**
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select branch: `main`
4. Click **"Save"**
5. Wait 1-2 minutes for deployment

### 5. Visit Your Live Site! 🎉

Your website will be live at: `https://YOUR_USERNAME.github.io`

---

## Method 2: Update Existing Repository

If you already have a `YourUsername.github.io` repository:

### Option A: Replace Everything

```bash
# Clone your existing repository
git clone https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
cd YOUR_USERNAME.github.io

# Remove old files (keep .git folder)
rm -rf * (but NOT .git folder!)

# Copy new website files into this folder
cp -r /path/to/new/files/* .

# Add profile photo to images/ folder

# Commit and push
git add .
git commit -m "Updated portfolio website with new design"
git push origin main
```

### Option B: Create a Branch (Test First)

```bash
# Create new branch
git checkout -b new-design

# Add your new files
git add .
git commit -m "New portfolio design"
git push origin new-design

# After testing, merge to main
git checkout main
git merge new-design
git push origin main
```

---

## 📝 Post-Deployment Checklist

After deploying, verify these items:

- [ ] Website loads at `https://YOUR_USERNAME.github.io`
- [ ] Profile photo displays correctly
- [ ] All sections are visible and formatted properly
- [ ] Navigation links work
- [ ] External links (LinkedIn, GitHub, Scholar) open correctly
- [ ] Mobile responsiveness works (test on phone)
- [ ] All content is up-to-date

---

## 🔧 Common Issues & Solutions

### Issue 1: Profile Photo Not Showing
**Solution**: 
- Ensure photo is named exactly `profile.png` (case-sensitive)
- Check it's in the `images/` folder
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)

### Issue 2: 404 Page Not Found
**Solution**:
- Verify repository name is exactly `YourUsername.github.io`
- Check GitHub Pages is enabled in Settings → Pages
- Wait 2-5 minutes after pushing changes

### Issue 3: Styling Looks Broken
**Solution**:
- Verify `css/style.css` file path is correct
- Check browser console for errors (F12)
- Ensure all files are in correct folders

### Issue 4: Links Don't Work
**Solution**:
- Check internal links use correct paths (e.g., `cv/cv.html`)
- Verify external links have `https://` prefix
- Test in multiple browsers

---

## 🎨 Customization After Deployment

### Update Your Information

1. **Edit content**: Modify `index.html`
2. **Change colors**: Edit `css/style.css` → `:root` variables
3. **Add pages**: Create new `.html` files and link them

### Make Changes

```bash
# Edit files locally
# Test changes (open index.html in browser)

# When satisfied, push to GitHub
git add .
git commit -m "Updated [what you changed]"
git push origin main

# Changes go live in 1-2 minutes
```

---

## 📊 Optional: Add Analytics

To track visitors, add Google Analytics:

1. Create Google Analytics account
2. Get your tracking ID
3. Add this code before `</head>` in `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

---

## 🌐 Optional: Custom Domain

To use your own domain (e.g., `shreyakapoor.com`):

1. **Buy a domain** from provider (Namecheap, GoDaddy, etc.)
2. **Update CNAME file**:
   ```
   yourdomain.com
   ```
3. **Configure DNS** at your domain provider:
   - Add A records pointing to GitHub's IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - Or add CNAME record: `YOUR_USERNAME.github.io`
4. **Enable in GitHub**: Settings → Pages → Custom domain

---

## 💡 Tips for Success

1. **Test locally first**: Open `index.html` in your browser before pushing
2. **Use meaningful commit messages**: Describe what you changed
3. **Regular updates**: Keep publications and experience current
4. **Backup**: Keep a local copy of your site files
5. **Browser testing**: Check in Chrome, Firefox, Safari
6. **Mobile check**: Always test on phone after changes

---

## 📞 Need Help?

If you encounter issues:

1. Check [GitHub Pages documentation](https://docs.github.com/en/pages)
2. Search [Stack Overflow](https://stackoverflow.com/questions/tagged/github-pages)
3. Review your repository settings
4. Check browser console for errors (F12)

---

**Your website is now live! Share it on LinkedIn and your CV! 🎉**

Remember: `https://YOUR_USERNAME.github.io`
