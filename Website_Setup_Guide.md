# Academic Website Setup Guide

## What I've Created

A clean, professional academic website (similar to the Vasquez example) with:
- ✅ Professional header with contact info
- ✅ Research interests summary
- ✅ Peer-reviewed publications
- ✅ Working papers & manuscripts under review
- ✅ Policy engagement section
- ✅ Teaching overview
- ✅ Recent activities
- ✅ Download CV link
- ✅ Mobile-responsive design
- ✅ Professional color scheme (dark blue #1F4788)

## Files Included

- **index.html** — Main website file (ready to use)

## How to Host It (Three Options)

### Option 1: GitHub Pages (FREE & EASIEST) ⭐ RECOMMENDED

1. **Create a GitHub account** (if you don't have one): https://github.com/signup

2. **Create a new repository:**
   - Name it: `valentinkiefner.github.io` (replace with your GitHub username)
   - Make it public
   - Don't add README, .gitignore, or license

3. **Upload the website:**
   - Click "Add file" → "Upload files"
   - Drag and drop the `index.html` file
   - Click "Commit changes"

4. **Your website is live!**
   - Visit: `https://valentinkiefner.github.io/`
   - Custom domain available (optional): https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

### Option 2: WU Vienna Web Server

Contact WU's IT department about hosting space on the university server. They typically provide:
- `https://wu.ac.at/~kiefner/` or similar
- Email them your HTML files
- Usually free for faculty/researchers

### Option 3: Paid Web Hosting

- Bluehost, GoDaddy, Namecheap (~$3-10/month)
- Upload `index.html` via FTP
- Register custom domain (optional)

---

## Before Publishing: Important Updates

1. **Add CV file:**
   - Create a `files/` folder in your repository
   - Upload your CV as `CV_Kiefner_2025.pdf`
   - The website will link to it

2. **Update information:**
   - Replace "Valentin Kiefner" with your name
   - Update email and phone
   - Update publication DOIs/links if different
   - Update teaching courses
   - Update any outdated dates

3. **Add your photo (optional):**
   - Save a professional headshot as `images/profile.jpg`
   - Add this line after the `<h1>` in the HTML:
     ```html
     <img src="images/profile.jpg" style="width: 150px; border-radius: 8px; margin: 20px 0;">
     ```

---

## Customization Tips

### Change the color scheme:
Replace `#1F4788` (dark blue) with your preferred color:
- `#2c3e50` (dark grey-blue)
- `#0066cc` (bright blue)
- `#1a1a1a` (black)

### Add more sections:
Copy this template and add before `</main>`:
```html
<hr>
<section>
    <h2>Your New Section</h2>
    <p>Your content here</p>
</section>
```

### Update the footer:
Change the year and university name in the `<footer>` section.

---

## File Structure (after setup)

```
valentinkiefner.github.io/
├── index.html (main website)
├── files/
│   └── CV_Kiefner_2025.pdf (your CV)
└── images/
    └── profile.jpg (optional photo)
```

---

## What You Get

✅ Professional, clean design  
✅ Mobile-responsive (works on phones)  
✅ Fast loading  
✅ SEO-friendly  
✅ No coding knowledge required to maintain  
✅ Free if using GitHub Pages  
✅ Easy to update  

---

## Quick Comparison: GitHub Pages vs University Server vs Paid Hosting

| Feature | GitHub Pages | WU Server | Paid Hosting |
|---------|---|---|---|
| Cost | FREE | FREE | $3-15/month |
| Ease | Very Easy | Medium | Medium |
| Custom Domain | Yes (free) | Maybe | Yes (extra $) |
| Performance | Fast | Good | Good |
| Support | Community | WU IT | Provider |
| **Best For** | **Academics** | **Official profile** | **Brand domain** |

---

## Next Steps

1. **Choose hosting option** (GitHub Pages recommended)
2. **Create account** (if needed)
3. **Upload index.html**
4. **Add CV file** to `files/` folder
5. **Test on mobile** to ensure it looks good
6. **Share your website URL**

Your website will be live within minutes! 🎉

---

## Need Help?

- GitHub Pages setup: https://docs.github.com/en/pages/getting-started-with-github-pages
- HTML editing: Use any text editor (VS Code is free)
- Questions: Email me or check the web standards documentation

Enjoy your new academic website! 📄
