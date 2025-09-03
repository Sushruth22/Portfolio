# Sushruth Veldi - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript to showcase your professional experience, projects, and skills.

## Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and mobile navigation
- **Professional Sections**: Hero, About, Experience, Projects, Skills, and Contact
- **SEO Optimized**: Proper HTML structure and meta tags
- **Fast Loading**: Optimized CSS and minimal JavaScript

## File Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── IMG_9659.png       # Your profile image
└── README.md           # This file
```

## Setup Instructions

1. **Profile Image**:
   - Your profile image `IMG_9659.png` is already included
   - The image will be automatically cropped to fit the circular frame
   - Supported formats: JPG, PNG, WebP

2. **Open the Website**:
   - Double-click `index.html` to open in your browser
   - Or drag `index.html` into your browser window

3. **Customize Content**:
   - Edit `index.html` to update text content
   - Modify `styles.css` to change colors, fonts, and layout
   - Update `script.js` to add new functionality

## Customization Guide

### Colors
The main color scheme is defined in `styles.css`:
- Primary Blue: `#2563eb`
- Secondary Blue: `#1d4ed8`
- Accent Yellow: `#fbbf24`
- Text Colors: Various shades of gray

### Fonts
The website uses the Inter font family from Google Fonts. You can change this by:
1. Going to [Google Fonts](https://fonts.google.com/)
2. Selecting a new font
3. Updating the font import in `index.html`
4. Changing the `font-family` property in `styles.css`

### Content Updates
To update your information:

1. **Personal Details**: Edit the hero section in `index.html`
2. **Experience**: Modify the timeline items in the experience section
3. **Projects**: Update the project cards with your own projects
4. **Skills**: Adjust the skill categories and items
5. **Contact**: Update your contact information and social links

### Adding New Sections
To add a new section:

1. Add the HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Update the navigation menu
4. Add any JavaScript functionality in `script.js`

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

1. **Optimize Images**: Compress your profile image to reduce file size
2. **Minimize CSS/JS**: Consider minifying files for production
3. **Use WebP**: Convert images to WebP format for better compression
4. **Lazy Loading**: Consider implementing lazy loading for images if you add more

## Deployment

To deploy your portfolio online:

1. **GitHub Pages** (Free):
   - Create a GitHub repository
   - Upload your files
   - Enable GitHub Pages in repository settings

2. **Netlify** (Free):
   - Drag and drop your folder to Netlify
   - Get a free subdomain

3. **Vercel** (Free):
   - Connect your GitHub repository
   - Automatic deployments

4. **Traditional Hosting**:
   - Upload files via FTP to your web hosting provider

## Customization Examples

### Changing the Color Scheme
```css
/* In styles.css, update these variables */
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    --accent-color: #your-color;
}
```

### Adding a New Project
```html
<!-- In index.html, add this inside the projects-grid -->
<div class="project-card">
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description goes here.</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Live Demo</a>
            <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
        </div>
    </div>
</div>
```

## Support

If you need help customizing your portfolio:

1. Check the HTML structure in `index.html`
2. Review the CSS classes in `styles.css`
3. Ensure your profile image is properly named and sized
4. Test in different browsers and devices

## License

This portfolio template is free to use and modify for personal and commercial projects.

---

**Good luck with your portfolio!** 🚀
