# Flutter Developer Portfolio Website

Professional portfolio website for Ohimuzaneme Abudu-Sule, Senior Flutter Developer, built using the "Read Only" template by HTML5 UP.

**Live Site:** [https://suleohis.github.io](https://suleohis.github.io)

## 🚀 Quick Start

### Local Development

1. Clone or navigate to this repository
2. Open `index.html` in a web browser, or use a local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Then visit http://localhost:8000 in your browser
```

### GitHub Pages Deployment

1. Create a new repository named `suleohis.github.io`
2. Push this folder's contents to the repository
3. GitHub Pages will automatically deploy from the main branch
4. Visit https://suleohis.github.io to see your live site

## 📁 File Structure

```
Resume/
├── index.html              # Main portfolio page
├── assets/
│   ├── css/
│   │   ├── main.css       # Template styles
│   │   └── custom.css     # Custom portfolio styles
│   ├── js/                # JavaScript files
│   ├── sass/              # SASS source files (optional)
│   └── webfonts/          # Font files
├── images/
│   ├── profile_pic.jpg    # Your profile photo
│   ├── oyanow_courier/    # OyaNow Delivery app screenshots
│   ├── oyanow_merchant/   # OyaNow Restaurant app screenshots
│   └── ...
├── README.md              # This file
└── LICENSE.txt            # Template license
```

## 🖼️ Updating Images

### Profile Photo
- **Location:** `images/profile_pic.jpg`
- **Current:** Already set to your profile photo
- **To update:** Replace `images/profile_pic.jpg` with your new photo
- **Recommended size:** 400x400px or larger (square format)
- **Format:** JPG or PNG

### App Screenshots

#### OyaNow Delivery (Driver App)
- **Location:** `images/oyanow_courier/`
- **Current files:** `one.png`, `two.png`, `three.png`, `four.png`
- **Format:** PNG (portrait orientation, mobile screenshot format)
- **To update:** Replace the files in `images/oyanow_courier/` folder

#### OyaNow Restaurant (Restaurant Partner App)
- **Location:** `images/oyanow_merchant/`
- **Current files:** `one.png`, `two.png`, `three.png`
- **Format:** PNG (portrait orientation, mobile screenshot format)
- **To update:** Replace the files in `images/oyanow_merchant/` folder

## ✏️ Customization Guide

### Updating Contact Information

In `index.html`, find the contact section (around line 260) and update:
- Email links: `href="mailto:your-email@example.com"`
- Phone links: `href="tel:+1234567890"`
- Social media URLs

### Adding New Apps

To add a new published app:

1. Add screenshots to a new folder in `images/` (e.g., `images/new_app_name/`)
2. In `index.html`, find the "Published Apps" section (`id="apps"`)
3. Copy one of the existing `<article>` blocks
4. Update the content:
   - App name
   - Description
   - Key features list
   - Tech stack
   - Play Store link
   - Screenshot paths

### Modifying Skills

In `index.html`, find the "Skills" section (`id="skills"`) around line 180.
- Skills are organized in categories with `<h4>` headings
- Each skill is an `<li>` with an icon class
- Icons use Font Awesome (e.g., `icon brands fa-flutter`)

### Updating Experience

Find the "Experience" section (`id="experience"`) around line 220.
- Each job is an `<article>` element
- Update company name, dates, and bullet points

## 🎨 Styling

### Custom Styles
Custom styles are in `assets/css/custom.css`. Key customizations:
- Prominent Published Apps section with accent colors
- Hover effects on Play Store buttons
- Screenshot gallery hover animations
- Responsive design for mobile devices

### Color Scheme
The primary accent color is `#4acaa8` (teal green). To change:
1. Open `assets/css/custom.css`
2. Find and replace `#4acaa8` with your preferred color
3. Also update `#3eb89a` (hover state) accordingly

## 📱 Mobile Responsiveness

The site is fully responsive and tested on:
- Desktop (1920px and above)
- Tablet (768px - 1024px)
- Mobile (320px - 767px)

Test responsiveness:
1. Open in browser
2. Open Developer Tools (F12)
3. Toggle device toolbar (Ctrl+Shift+M)
4. Test different screen sizes

## ⚡ Performance Optimization

Current optimizations:
- ✅ Lazy loading for images
- ✅ Compressed images
- ✅ Minified CSS/JS (template default)
- ✅ Relative paths for GitHub Pages compatibility
- ✅ Semantic HTML for SEO

### To further optimize:
1. Compress images using tools like TinyPNG or ImageOptim
2. Consider using WebP format for images
3. Run Lighthouse audit in Chrome DevTools

## 🔍 SEO

The site includes:
- Descriptive title tag
- Meta description optimized for Flutter developer keywords
- Open Graph tags for social media sharing
- Semantic HTML structure
- Alt text for images

## 🛠️ Troubleshooting

### Images not loading on GitHub Pages
- Ensure all paths are relative (no `/` at the start)
- Check file names match exactly (case-sensitive on GitHub)
- Verify images are committed to the repository

### Styles not applying
- Clear browser cache (Ctrl+Shift+R)
- Check that `custom.css` exists in `assets/css/`
- Verify the CSS link in `index.html` (line 23)

### Links not working
- Ensure all external links have `target="_blank" rel="noopener noreferrer"`
- Test `mailto:` and `tel:` links on mobile devices

## 📄 License

### Template License
The HTML5 UP "Read Only" template is licensed under Creative Commons Attribution 3.0 (CCA 3.0).
- Template by [HTML5 UP](https://html5up.net)
- Free for personal and commercial use with attribution

### Portfolio Content
Portfolio content (text, images, personal information) © 2026 Ohimuzaneme Abudu-Sule. All rights reserved.

## 📞 Support

For questions about customizing this portfolio:
- Email: nemesule@gmail.com
- GitHub: [@suleohis](https://github.com/suleohis)

---

**Built with:** HTML5, CSS3, JavaScript  
**Template:** Read Only by HTML5 UP  
**Last Updated:** January 2026
