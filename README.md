# Gupth Marketing Website

A modern, responsive marketing website for Gupth - the secure, local password manager.

## Features

- **Modern Design**: Dark theme matching the Gupth app aesthetic
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive**: Smooth animations, hover effects, and interactive elements
- **SEO Optimized**: Meta tags, structured data, and semantic HTML
- **Accessible**: Keyboard navigation and screen reader support
- **Fast Loading**: Optimized CSS and JavaScript for quick page loads

## File Structure

```
gupth-web/
├── index.html          # Main homepage
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── gupth-app.zip       # Your Gupth application (add this)
```

## Setup Instructions

### 1. Add Your App File
- Place your `gupth-app.zip` file in the root directory
- The download button will automatically link to this file

### 2. Customize Content
- Edit `index.html` to update any text, links, or contact information
- Modify `styles.css` to change colors, fonts, or layout
- Update `script.js` to add or modify interactive features

### 3. Host the Website

#### Option A: GitHub Pages (Free)
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch" and choose "main"
5. Your site will be available at `https://yourusername.github.io/repository-name`

#### Option B: Netlify (Free)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Your site will be live instantly with a custom URL

#### Option C: Vercel (Free)
1. Go to [vercel.com](https://vercel.com)
2. Import your project from GitHub or upload files
3. Deploy with one click

#### Option D: Traditional Web Hosting
1. Upload all files to your web hosting provider
2. Ensure `index.html` is in the root directory
3. Your site will be live at your domain

### 4. Custom Domain (Optional)
- Purchase a domain name (e.g., `gupth.com`)
- Point your domain to your hosting provider
- Update any hardcoded URLs in the code

## Customization Guide

### Colors
The main color scheme uses:
- Primary: `#667eea` (Blue)
- Secondary: `#764ba2` (Purple)
- Success: `#10b981` (Green)
- Background: `#0a0a0a` (Dark)

To change colors, search and replace in `styles.css`:
```css
/* Find and replace these values */
#667eea  /* Primary blue */
#764ba2  /* Primary purple */
#10b981  /* Success green */
```

### Fonts
The site uses Inter font from Google Fonts. To change:
1. Update the Google Fonts link in `index.html`
2. Update the `font-family` in `styles.css`

### Content Updates
- **Hero Section**: Update the main headline and description
- **Features**: Modify the feature cards in the features section
- **Download**: Update version number, file size, and download link
- **About**: Customize the about section with your story

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Add any JavaScript functionality in `script.js`
4. Update navigation menu if needed

## SEO Optimization

The website includes:
- Meta description and keywords
- Open Graph tags for social sharing
- Semantic HTML structure
- Fast loading times
- Mobile-friendly design

## Browser Support

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## Performance

- Optimized CSS and JavaScript
- Lazy loading for images
- Smooth animations with CSS transforms
- Minimal external dependencies

## Support

For questions or issues:
1. Check the code comments in each file
2. Test in different browsers
3. Validate HTML and CSS
4. Check browser console for JavaScript errors

## License

This website template is free to use and modify for your Gupth marketing needs.

---

**Ready to launch?** Just add your `gupth-app.zip` file and deploy to your chosen hosting platform!
