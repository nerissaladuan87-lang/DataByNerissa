# 🚀 Deploy to GitHub Pages — Step-by-Step Guide

Your portfolio is now **secured and ready** for public hosting. Follow these steps to go live.

---

## ✅ Pre-Deployment Checklist

- [x] Security headers configured (_headers file)
- [x] robots.txt created for SEO
- [x] .gitignore set up to prevent accidental commits
- [x] .nojekyll file added (disables Jekyll processing)
- [x] Security meta tags added to all HTML pages
- [x] Contact links verified (email, LinkedIn, WhatsApp)
- [ ] Your profile photos added to images/ folder
- [ ] Your CV saved as cv.pdf in the root folder

---

## 🎯 Step 1: Create a GitHub Account

If you don't have one:
1. Go to https://github.com
2. Click **Sign up**
3. Choose a username (this becomes part of your URL)
4. Verify your email address

---

## 🎯 Step 2: Create Your GitHub Repository

1. Log in to GitHub
2. Click the **+** icon (top right) → **New repository**
3. **Repository name:** Use exactly this format:
   ```
   yourusername.github.io
   ```
   ⚠️ **IMPORTANT:** Replace `yourusername` with your actual GitHub username
   
   **Example:** If your username is `nerissa-laduan`, name it `nerissa-laduan.github.io`

4. Add description (optional): "My data analytics portfolio"
5. Select **Public** (required for GitHub Pages)
6. Check ✓ "Add a README file"
7. Click **Create repository**

---

## 🎯 Step 3: Upload Your Portfolio Files

### Option A: Using GitHub Web Interface (Easiest for beginners)

1. Go to your new repository
2. Click **Add file** → **Upload files**
3. Drag and drop all portfolio files:
   - `index.html`
   - `about.html`
   - `contact.html`
   - `skills.html`
   - `projects.html`
   - `services.html`
   - `style.css`
   - `cv.pdf`
   - `.gitignore`
   - `robots.txt`
   - `.nojekyll`
   - Entire `images/` folder

4. Scroll down and click **Commit changes**

### Option B: Using Git Command Line (Faster if you're comfortable with terminal)

```bash
# Navigate to your portfolio folder
cd "c:\Users\nerissa\Desktop\Website portfolio\portfolio"

# Initialize git (if not already done)
git init

# Add all files
git add .

# Create first commit
git commit -m "Initial portfolio commit"

# Add your GitHub repository as remote
# Replace yourusername with your actual GitHub username
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

---

## 🎯 Step 4: Enable GitHub Pages

1. Go to your repository
2. Click **Settings** (top right)
3. Click **Pages** (left sidebar)
4. Under "Build and deployment":
   - **Source:** Select **Deploy from a branch**
   - **Branch:** Select **main**
   - **Folder:** Select **/ (root)**
5. Click **Save**

**Wait 1-2 minutes** for GitHub to build your site.

---

## 🎯 Step 5: Verify Your Live Site

Your portfolio is now live! 🎉

**Your URL:** `https://yourusername.github.io`

Examples:
- If username is `nerissa-laduan` → `https://nerissa-laduan.github.io`
- If username is `datanerissa` → `https://datanerissa.github.io`

---

## 📱 Testing Checklist

Once live, test these on your phone and desktop:

- [ ] Homepage loads with profile photo
- [ ] Navigation works (all links clickable)
- [ ] About page displays correctly
- [ ] Projects page shows project images
- [ ] Services page is readable
- [ ] Skills section displays all skills
- [ ] Contact page shows all contact methods
- [ ] Email link (📧) opens your email client
- [ ] LinkedIn link opens in new tab
- [ ] WhatsApp link opens chat
- [ ] CV download works
- [ ] Mobile view (hamburger menu) works

---

## 🔗 Optional: Use a Custom Domain

If you want to use your own domain (like `yourdomain.com`):

1. Buy a domain from:
   - GoDaddy (godaddy.com)
   - Namecheap (namecheap.com)
   - Domain.com

2. In GitHub, go to **Settings** → **Pages**

3. Under "Custom domain", enter your domain name

4. In your domain registrar's DNS settings, add these records:
   ```
   A record:    185.199.108.153
   A record:    185.199.109.153
   A record:    185.199.110.153
   A record:    185.199.111.153
   CNAME:       yourusername.github.io
   ```

5. Wait 24 hours for DNS to propagate

---

## 🔒 Security Best Practices

✅ **You're already protected:**
- HTTPS enabled automatically (green lock icon)
- No sensitive data in code
- robots.txt configured
- Security headers in place
- Contact form uses mailto: (no backend vulnerability)

⚠️ **Remember:**
- Never commit API keys or passwords
- Keep CV up to date
- Review contact info yearly

---

## 🚀 Next Steps

1. **Share your portfolio:**
   - LinkedIn bio: Add link to your portfolio
   - Resume/CV: Include the URL
   - Job applications: Paste link in "portfolio website" field
   - Freelance profiles: Upwork, Fiverr, etc.

2. **Keep it updated:**
   - Add new projects as you complete them
   - Update skills section with new tools
   - Refresh CV when experience changes

3. **Monitor visitors:**
   - Optional: Add Google Analytics to track traffic
   - See what projects get the most clicks

---

## ❓ Troubleshooting

**Site shows 404 error:**
- Wait 2-3 minutes after uploading
- Make sure file names match URLs exactly (case-sensitive)
- Check that index.html is in the root folder

**Images not showing:**
- Verify image files are in the `images/` folder
- Check file names match `src` in HTML (lowercase)
- Use relative paths: `src="images/profile.jpg"`

**Styles not loading:**
- Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
- Check that style.css is in the root folder

**Can't push with Git:**
- Generate GitHub SSH key: https://docs.github.com/en/authentication/connecting-to-github-with-ssh
- Or use personal access token: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens

---

## 📚 More Resources

- GitHub Pages Docs: https://pages.github.com
- How to use Git: https://git-scm.com/doc
- Markdown guide: https://www.markdownguide.org/

---

**Congratulations! Your portfolio is live! 🎉**

*Questions? Reply to this guide or check GitHub's help docs.*
