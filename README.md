# Awesome-Site Template

Custom Example:
![Custom Example](https://raw.githubusercontent.com/Linux-jam/Photo-Gallery/refs/heads/main/awesome-site-demo.png)  
*A modern, responsive personal website template*

## ✨ Features

- **Clean & Modern Design**: Sleek gradient background with fixed header and interactive footer.
- **Full Responsive**: Perfectly adapts to mobile, tablet, and desktop screens.
- **Social Media Ready**: 12+ pre-linked social icons (X, GitHub, YouTube, etc.).
- **MIT Licensed**: Free to use, modify, and distribute.
- **Multi-language Font Support**: Auto-optimized for Japanese/Chinese characters.
- **Lightweight**: Pure HTML/CSS with no JavaScript dependency.

## 🛠️ Quick Start

1. **Clone the repo**:
   ```bash
   git clone https://github.com/AM-Software-Team/awesome-site-template.git
   ```

2. **Edit content**:
   - Replace social links in `footer.html`
   - Update navigation in `header.html`
   - Customize main content in `index.html`

3. **Deploy anywhere**:
   - Works with GitHub Pages, Netlify, Vercel, etc.

## 🎨 Customization Guide

### Change Colors
Edit these variables in `base.css`:
```css
.nav-header { background: #223a6d; }
body { background: linear-gradient(120deg, #2b6cb0 0%, #63b3ed 100%); }
```

### Add Social Icons
1. Place SVG in `/assets/svg/`
2. Add to `footer.html`:
```html
<a href="YOUR_LINK" target="_blank" rel="noopener noreferrer" title="PLATFORM">
  <img src="/assets/svg/YOUR_ICON.svg" alt="PLATFORM" width="24" height="24">
</a>
```

## 📱 Responsive Breakpoints
| Device       | Header Height | Icon Size |
|--------------|---------------|-----------|
| Desktop      | 56px          | 40px      |
| Mobile       | 44px          | 32px      |

## 🌟 Why Choose This Template?

✅ **Zero Bloat** - No unnecessary frameworks  
✅ **Dark Mode Ready** - Built with accessible contrasts  
✅ **Performance Optimized** - 95+ Lighthouse score out-of-the-box  

## 📜 License
Unlicense @ 2025 [AM Software Team](https://github.com/ams-www)

> "Perfect for developers, creators, and professionals who want a polished web presence without complexity."
