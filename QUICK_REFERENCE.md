# 📝 Quick Reference — Common Updates

## 🎨 Change Colors
**File:** `style.css` (line 30)
```css
:root {
  --accent: #0f6a92;  /* ← Change this hex code */
}
```

Color ideas:
- Purple: `#7c3aed`
- Green: `#16a34a`
- Blue: `#2563eb`
- Teal: `#0d9488`

---

## 👤 Update Your Name Everywhere
Search for `Nerissa` or `DataByNerissa` and replace with your name.

**Key locations:**
- `index.html` — Nav logo, hero section, footer
- `about.html` — Page hero, footer
- `contact.html` — Nav logo, footer
- All other HTML files — Nav logo, footer

---

## 📧 Update Contact Info
**File:** `contact.html`

```html
<!-- Email -->
<a href="mailto:your.email@gmail.com">

<!-- LinkedIn -->
<a href="https://www.linkedin.com/in/your-profile/">

<!-- WhatsApp -->
<a href="https://wa.me/YOUR_PHONE_NUMBER">
```

**WhatsApp Format:** 
- Remove `+` sign
- Keep country code (63 for Philippines)
- No spaces or dashes
- Example: `639171234567`

---

## 📸 Add Your Photos
1. Create `images/` folder (if not exists)
2. Add these images (JPG or PNG):
   - `profile.jpg` — Homepage photo (400×500px portrait)
   - `about.jpg` — About page photo (can be same as profile)
   - `project1.jpg` — Project 1 screenshot
   - `project2.jpg` — Project 2 screenshot
   - `project3.jpg` — Project 3 screenshot

**Important:** Use lowercase filenames!

---

## 📄 Update Your CV
1. Export resume as PDF
2. Save as `cv.pdf` in the root folder
3. Test download link on homepage

---

## 🎯 Update Bio
**File:** `about.html` (search for `<h2>` with your story)
Replace the bio paragraphs with your own story.

---

## 💼 Update Skills
**File:** `skills.html`

Add/edit skill categories and proficiency levels in the skills grid.

---

## 🚀 Update Projects
**File:** `projects.html`

Update:
- Project titles
- Project descriptions
- `images/project1.jpg`, `project2.jpg`, `project3.jpg`
- Links to GitHub repos (if applicable)

---

## 🔧 Update Services
**File:** `services.html`

Add/edit:
- Service titles
- Service descriptions
- Pricing tiers (optional)
- Call-to-action text

---

## 📍 Update Location
**File:** `contact.html` (line ~357)
```html
Diffun, Quirino, Philippines
```

---

## ✅ Annual Maintenance
- [ ] Update year in footer (2026, 2027, etc.)
- [ ] Add new projects from past year
- [ ] Update CV with new skills/experience
- [ ] Refresh profile photo (optional)
- [ ] Check all external links work
- [ ] Test on mobile devices

---

## 🔄 How to Push Changes to GitHub

```bash
# Navigate to your portfolio folder
cd "c:\Users\nerissa\Desktop\Website portfolio\portfolio"

# Add all changes
git add .

# Describe what you changed
git commit -m "Update projects and skills"

# Upload to GitHub
git push
```

Site updates live within 1-2 minutes!

---

## 🆘 Need Help?

**Problem:** Changes not showing on website
**Solution:** 
1. Wait 2-3 minutes for GitHub to rebuild
2. Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)

**Problem:** Images not loading
**Solution:** 
1. Check filename matches exactly (case-sensitive)
2. Verify images are in `images/` folder
3. Use relative paths: `src="images/filename.jpg"`

**Problem:** Styles look wrong
**Solution:**
1. Make sure `style.css` is in the root folder
2. Check for typos in file names
3. Clear browser cache

---

## 📊 View Traffic (Optional)
GitHub provides basic traffic stats:
1. Go to your repository
2. Click **Insights** → **Traffic**
3. See how many people visited your portfolio!

---

**Keep your portfolio updated = Keep your network impressed!** 🚀
