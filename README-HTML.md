# Portfolio - HTML/CSS/JavaScript Version

This is a pure HTML, CSS, and JavaScript version of the portfolio, converted from the Next.js/React version. No build tools or dependencies required!

## Files Structure

- `index.html` - Main HTML file with all portfolio sections
- `styles.css` - All styling (converted from Tailwind/SCSS)
- `script.js` - All JavaScript functionality
- `images/` - Image assets (copy from `public/images/` folder)

## How to Use

1. **Copy Images**: Copy the `public/images` folder to the root directory (same level as `index.html`)

2. **Open in Browser**: Simply open `index.html` in any modern web browser

3. **Or Use a Local Server** (recommended for better performance):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have it)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

## Features

✅ **All Original Features Preserved:**
- Hero section with animated roles
- Stats counter
- About section
- Experience timeline tree
- Projects grid with modal
- Achievements & Certifications
- Timeline carousel
- Testimonials carousel
- Services grid
- Skills/Expertise section
- WhatsApp button
- Footer with contact info

✅ **Interactive Features:**
- Dark/Light theme toggle (saved to localStorage)
- Mobile responsive navigation
- Smooth scrolling
- Project modal popups
- Draggable testimonials carousel
- Scroll animations
- Header scroll effect

## Browser Support

Works in all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

## Customization

### Change Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary: 262.1 83.3% 57.8%; /* Purple */
    /* ... other colors */
}
```

### Update Content
Edit the `portfolioData` object in `script.js`:
```javascript
const portfolioData = {
    personal: { /* ... */ },
    experience: [ /* ... */ ],
    projects: [ /* ... */ ],
    // ... etc
};
```

### Modify Styles
All styles are in `styles.css` - no build step needed, just edit and refresh!

## Notes

- Images should be in `images/` folder (relative to `index.html`)
- Theme preference is saved in browser localStorage
- All animations use CSS and vanilla JavaScript (no libraries)
- Fully responsive design
- SEO-friendly HTML structure

## License

Same as the original portfolio.

