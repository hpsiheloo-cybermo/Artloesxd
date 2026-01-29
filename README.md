# Ink_Hiruz Art Portfolio

🎨 **Protected Art Portfolio Website with Copyright Protection**

A professional portfolio showcasing original artwork with built-in copyright protection features including watermarks, right-click protection, and reverse image search tools.

## 🌐 Live Website

Once deployed, your site will be available at:
```
https://[YOUR-GITHUB-USERNAME].github.io/[REPOSITORY-NAME]/
```

## ✨ Features

### Copyright Protection
- ✅ Right-click disabled with alerts
- ✅ Automatic watermarks on all artwork
- ✅ Low-resolution previews (1080px max)
- ✅ Copyright notices on image hover
- ✅ Keyboard shortcuts blocked (Save, Print, Screenshot)
- ✅ Text selection disabled

### Built-in Tools
- 🔍 **Reverse Image Search** - Find unauthorized uses
- 💧 **Watermark Tool** - Add signatures to images
- 📐 **Resolution Optimizer** - Resize for social media
- 🔗 **Quick Links** - Copyright registration & reporting

### Design
- Elegant serif typography (Bodoni Moda)
- Responsive mobile-friendly layout
- Smooth animations and interactions
- Professional gallery presentation

## 🚀 Quick Start - Deploy to GitHub Pages

### Step 1: Fork or Download
- Download this repository
- Or fork it to your GitHub account

### Step 2: Upload to GitHub
1. Create a new repository on GitHub
2. Name it (e.g., `ink-hiruz-portfolio`)
3. Make it **Public**
4. Upload all files
5. **Rename `art-portfolio.html` to `index.html`** (Important!)

### Step 3: Enable GitHub Pages
1. Go to repository **Settings**
2. Click **Pages** in the left sidebar
3. Under **Source**: Select "Deploy from a branch"
4. Choose **main** branch and **/ (root)** folder
5. Click **Save**
6. Wait 1-2 minutes for deployment

### Step 4: Visit Your Site!
Your site will be live at:
```
https://[your-username].github.io/[repository-name]/
```

## 📝 Customization

### Add Your Artwork
1. Prepare your images:
   - Resize to max 1080px (longest side)
   - Convert to 72 DPI
   - Save as JPEG with 85% quality
   
2. Edit `index.html`:
   - Replace placeholder images with your artwork
   - Update artwork titles and descriptions
   - Add copyright registration numbers

### Customize Branding
Already set to **Ink_Hiruz** - to change:
- Search and replace "Ink_Hiruz" in `index.html`
- Update watermark text
- Modify copyright notices

### Change Colors
Edit CSS variables in the `<style>` section:
```css
:root {
    --primary: #1a1a1a;    /* Dark text */
    --accent: #d4a574;     /* Gold accent */
    --bg: #faf9f7;         /* Background */
    --text: #2d2d2d;       /* Body text */
    --border: #e8e6e1;     /* Borders */
}
```

## 🎨 Adding New Artwork

Copy this template and paste it in the gallery section:

```html
<div class="art-card">
    <div class="art-image-container">
        <div class="watermark">© Ink_Hiruz</div>
        <img src="your-image.jpg" alt="Artwork description" class="art-image">
        <div class="copyright-overlay">
            <p class="copyright-text">© 2026 Ink_Hiruz. All Rights Reserved. Registration #XXXXX</p>
        </div>
    </div>
    <div class="art-info">
        <h3>Your Artwork Title</h3>
        <p>Medium: Digital Art / Size: 3000x4000px</p>
        <div class="art-meta">
            <span class="art-date">January 2026</span>
            <span class="copyright-badge">© Registered</span>
        </div>
    </div>
</div>
```

## 🛡️ Copyright Protection Features

### What's Protected
- Images cannot be easily saved via right-click
- Watermarks visible on all artwork
- Low-resolution prevents print quality theft
- Copyright information always visible
- Keyboard shortcuts disabled

### What to Do Next
1. **Register Your Copyright**
   - US: https://www.copyright.gov/
   - International: Your country's IP office

2. **Monitor Your Work**
   - Use reverse image search monthly
   - Check Google Images, TinEye, Yandex
   - Keep records of unauthorized uses

3. **Report Infringements**
   - Instagram: Report → IP violation
   - Facebook: Report → IP violation
   - Google: DMCA takedown request

## 📱 Social Media Preparation

Before posting to Instagram/Facebook/Telegram:
1. Use the **Resolution Optimizer** tool on the site
2. Download the optimized version
3. Post the watermarked, low-res version
4. Keep original high-res files safe

## 🔧 Technical Details

### Browser Support
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

### File Structure
```
/
├── index.html          # Main website file
└── README.md          # This file
```

### No Backend Required
- Pure HTML/CSS/JavaScript
- No server needed
- No databases
- Completely static

## ⚠️ Important Notes

### Limitations
- Right-click protection can be bypassed by advanced users
- Screenshots can still be taken
- These protections deter casual theft, not determined pirates

### Best Practices
- Always keep high-resolution originals offline
- Register important works with copyright office
- Use watermarks on all public images
- Monitor your work regularly
- Document all unauthorized uses

## 🆘 Troubleshooting

**Site not loading?**
- Wait 2-3 minutes after enabling Pages
- Check file is named `index.html` (not `art-portfolio.html`)
- Ensure repository is Public
- Clear browser cache

**Images not showing?**
- Check image file paths
- Ensure images are in the same folder as index.html
- Use relative paths (e.g., `./image.jpg`)

**Tools not working?**
- Resolution Optimizer works fully
- Reverse Image Search opens search engines
- Watermark tool requires manual processing currently

## 📄 License

© 2026 Ink_Hiruz. All Rights Reserved.

This portfolio template can be used for personal portfolios. All artwork displayed is copyrighted by Ink_Hiruz.

## 🤝 Support

For issues or questions:
- Check GitHub Issues
- Review this README
- Contact via portfolio contact form

## 🎯 Next Steps

1. ✅ Deploy to GitHub Pages
2. ✅ Add your actual artwork
3. ✅ Register copyrights
4. ✅ Share your portfolio link
5. ✅ Set up monthly image monitoring
6. ✅ Start tracking your art across platforms

---

**Built with copyright protection in mind for artists who value their work.**

Made with 💙 for Ink_Hiruz
