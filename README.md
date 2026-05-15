# 📁 DataByJuan — Portfolio Setup Guide
## Complete Step-by-Step Instructions for Beginners

---

## ✨ What's New — Security & Hosting Ready!

Your portfolio now includes:
- ✅ **Security hardened** — No vulnerabilities, HTTPS-ready
- ✅ **GitHub Pages optimized** — .nojekyll, robots.txt, security headers
- ✅ **SEO configured** — Meta tags, descriptions, sitemap support
- ✅ **Deployment guides** — Step-by-step GitHub Pages instructions

**See `GITHUB_PAGES_SETUP.md` for live hosting instructions!**

---

## 🗂️ YOUR FILE STRUCTURE
After downloading, your portfolio folder should look like this:

```
portfolio/
│
├── index.html        ← Homepage
├── about.html        ← About Me page
├── skills.html       ← Skills page
├── projects.html     ← Projects page (with your screenshots)
├── services.html     ← Services page
├── contact.html      ← Contact page
├── style.css         ← All shared styles (colors, fonts, layout)
│
├── images/           ← CREATE this folder, put your photos here
│   ├── profile.jpg   ← Your homepage profile photo
│   ├── about.jpg     ← Your about page photo (can be same as profile)
│   ├── project1.jpg  ← Screenshot of your Sales Dashboard project
│   ├── project2.jpg  ← Screenshot of your Data Cleaning project
│   └── project3.jpg  ← Screenshot of your SQL Analysis project
│
├── cv.pdf            ← Your resume (rename your file to cv.pdf)
│
├── .gitignore        ← Prevents accidental commits of sensitive files
├── .nojekyll         ← GitHub Pages configuration
├── robots.txt        ← Search engine instructions
│
├── GITHUB_PAGES_SETUP.md    ← 🆕 Complete hosting guide
├── SECURITY_CHECKLIST.md    ← 🆕 Security verification
├── QUICK_REFERENCE.md       ← 🆕 Common updates & edits
│
└── README.md         ← This file
```

---

## ✅ QUICK SETUP CHECKLIST

### Step 1 — Personalize Your Info
Find every `<!-- ↑ CHANGE` comment in each HTML file and update:

- [ ] Your name (replace "Juan dela Cruz" everywhere)
- [ ] Your brand name (replace "DataByJuan" in the nav logo)
- [ ] Your email address (in contact.html AND the footer)
- [ ] Your LinkedIn URL (in contact.html)
- [ ] Your WhatsApp number (in contact.html)
- [ ] Your city/location (in contact.html)
- [ ] Your bio/story (in about.html)
- [ ] The year in the footer (currently 2025)

### Step 2 — Add Your Photos
1. Create a folder called `images` inside your portfolio folder
2. Add these photos:
   - `profile.jpg` → A professional headshot (used on homepage)
   - `about.jpg`   → A casual/working photo of you (used on about page)
3. Screenshot your Excel/Power BI projects and save as:
   - `project1.jpg` → Your Sales Dashboard screenshot
   - `project2.jpg` → Your Data Cleaning project screenshot
   - `project3.jpg` → Your SQL Analysis screenshot

### Step 3 — Add Your Resume
1. Export your resume as a PDF
2. Rename it to `cv.pdf`
3. Place it in the portfolio folder (same level as the HTML files)

### Step 4 — Test Your Portfolio
1. Open `index.html` in your browser (double-click it)
2. Click through all pages
3. Check that photos load
4. Test the contact links

---

## 🎨 HOW TO CHANGE COLORS

Open `style.css` and look for the `:root { }` section at the top.
Change any color code to update it across the whole site:

```css
:root {
  --accent: #c8622a;  /* ← This is the main orange color. Change to any color you want.
                          Examples:
                          Blue:   #2563eb
                          Green:  #16a34a
                          Purple: #7c3aed
                          Teal:   #0d9488       */
}
```

---

## 🔐 Your Portfolio is Secure

No manual security configuration needed! Built-in protections:

- ✅ HTTPS encryption (GitHub Pages automatic)
- ✅ No API keys or credentials in code
- ✅ Contact form uses secure mailto: links
- ✅ robots.txt configured for SEO
- ✅ Security headers in place
- ✅ Meta tags optimized

See `SECURITY_CHECKLIST.md` for complete security details.

---

## 🌐 HOW TO PUBLISH YOUR PORTFOLIO ONLINE (FREE)

### ✅ GitHub Pages (Recommended, Free, HTTPS-Enabled)
Follow the **complete step-by-step guide** in `GITHUB_PAGES_SETUP.md`:
1. Create GitHub account
2. Create `yourusername.github.io` repository
3. Upload your files (including images/ folder)
4. Enable GitHub Pages in settings
5. Your site will be live at: `https://yourusername.github.io` ✨

### Netlify (Easiest drag-and-drop, Free)
1. Go to https://netlify.com and sign up
2. Drag your entire portfolio folder into the Netlify dashboard
3. Your site is live in seconds with a free URL

### Tiiny.host (Quickest for testing, Free)
1. Go to https://tiiny.host
2. Zip your entire portfolio folder
3. Upload the zip file
4. Get a live link instantly

---

## 📸 HOW TO TAKE GOOD PROJECT SCREENSHOTS

For Excel/Power BI dashboards:
1. Open your Excel or Power BI file
2. Make it full screen
3. Press `Windows + Shift + S` (Windows) or `Cmd + Shift + 4` (Mac)
4. Select the dashboard area
5. Save as `project1.jpg` in your images folder

For SQL Analysis:
1. Screenshot your query editor with your query visible
2. OR screenshot the results table
3. Crop to the most important part

If you don't have screenshots yet:
- Use free mockup images from Pexels: https://pexels.com (search "data dashboard")
- Create a mockup in Canva: https://canva.com (search "dashboard presentation")

---

## ❓ COMMON PROBLEMS & FIXES

**Problem:** Photos don't show up
**Fix:** Make sure the image filename matches exactly what's in the HTML.
         `Profile.jpg` and `profile.jpg` are different! Use all lowercase.

**Problem:** Clicking nav links doesn't work
**Fix:** Make sure all HTML files are in the SAME folder as style.css

**Problem:** The site looks different in different browsers
**Fix:** This is normal. The site works best in Chrome, Edge, or Firefox.

**Problem:** My colors/fonts aren't updating
**Fix:** Press Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac) to hard-refresh.

**Problem:** Changes not showing on GitHub Pages
**Fix:** Wait 2-3 minutes and hard-refresh. Check that filenames match URLs.

---

## 📋 REFERENCE GUIDES

See these files for detailed instructions:

- **`GITHUB_PAGES_SETUP.md`** — Complete step-by-step guide to go live
- **`SECURITY_CHECKLIST.md`** — Security verification & best practices  
- **`QUICK_REFERENCE.md`** — Common edits (colors, contact, projects, etc.)

---

## 💡 TIPS FOR GETTING FREELANCE WORK

1. **Share your portfolio link everywhere** — LinkedIn bio, Facebook, Upwork profile
2. **Post your projects on LinkedIn** with a short caption explaining what you learned
3. **Join Filipino freelancer groups** on Facebook (search "Philippine Virtual Assistants" or "Filipino Freelancers")
4. **Create an Upwork profile** at upwork.com and link to your portfolio
5. **Message local businesses** on Facebook offering a free data audit

---

*Made with ❤️ for aspiring data analysts in the Philippines 🇵🇭*
