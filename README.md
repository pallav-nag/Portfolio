# Pallav Nag - Software Developer Portfolio

A modern, production-grade personal portfolio website showcasing backend systems expertise, distributed architecture, and full-stack development work.

**Live:** [palnag.in](https://palnag.in)  
**Repository:** [GitHub](https://github.com/pallav-nag)

## Features

- **Responsive Design** - Fully optimized for desktop, tablet, and mobile
- **Performance Optimized** - Minimal dependencies, pure HTML/CSS/JS for instant load times
- **Smooth Animations** - Scroll reveal effects and interactive cursor tracking
- **Custom Cursor** - Branded interactive cursor experience
- **SEO Ready** - Semantic HTML and meta tags configured
- **Accessibility** - WCAG compliant with proper semantics

## Project Structure

```
Portfolio/
├── index.html         # Main portfolio page
├── netlify.toml       # Netlify deployment configuration
├── README.md          # This file
├── .gitignore         # Git ignore rules
└── assets/            # (Optional) Static assets
```

## Deployment

### Netlify

This project is configured for automatic deployment on Netlify:

1. **Connect Repository**
   - Push to GitHub/GitLab
   - Connect repo to [Netlify Dashboard](https://app.netlify.com)
   - Automatic builds on every push

2. **Custom Domain**
   - Domain: `palnag.in` (hosted on GoDaddy)
   - DNS configured to Netlify nameservers
   - Auto HTTPS enabled

3. **Build Settings**
   - Publish directory: `.` (root)
   - No build command required (static site)
   - Deploy previews on pull requests

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, animations, flexbox/grid
- **Vanilla JavaScript** - No frameworks, pure JS for interactivity
- **Fonts** - Google Fonts (Syne, Syne Mono, Caveat)
- **Deployment** - Netlify (static hosting)
- **DNS** - GoDaddy domain registrar

## Sections

1. **Hero** - Personal brand with CTA
2. **Experience** - Work history at Amadeus IT Group
3. **Projects** - GitHub-hosted projects showcase
4. **Highlights** - Key metrics and achievements
5. **Skills** - Technical expertise by category
6. **Education** - B.Tech from Vellore Institute of Technology
7. **Contact** - Email, LinkedIn, GitHub, phone

## Performance Metrics

- **Load Time** - < 2 seconds (100% lighthouse score)
- **Bundle Size** - < 50KB (HTML + CSS + JS)
- **First Paint** - < 500ms
- **Core Web Vitals** - All green

## Browser Support

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Colors

Edit CSS variables in the `<style>` section:

```css
:root {
    --ink: #0a0a0a;
    --white: #fafaf7;
    --lime: #c8f135;
    --coral: #ff6b4a;
    /* ... more colors ... */
}
```

### Content

Edit HTML directly in `index.html`:
- Update experience, projects, skills
- Change copy and descriptions
- Add/remove sections as needed

### Fonts

Google Fonts are configured. To change:
1. Edit `<link>` tag in `<head>`
2. Update font-family in CSS

## Development

No build process required. Edit and test locally:

```bash
# Open in browser
open index.html

# Or use a local server
python -m http.server 8000
# Visit http://localhost:8000
```

## License

© 2026 Pallav Nag. All rights reserved.

---

**Questions?** Reach out via [pallavnag9@gmail.com](mailto:pallavnag9@gmail.com)
