# Prabhat Celebrations - Wedding Venue Website

A beautiful, modern, and responsive website template for a wedding venue business.

## Features

- ✨ **Modern Design**: Elegant and sophisticated design with a golden color scheme
- 📱 **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- 🎨 **Beautiful UI**: Clean and professional interface with smooth animations
- 🚀 **Fast Performance**: Lightweight and optimized for quick loading
- 📧 **Contact Form**: Ready-to-use contact form for inquiries
- 🖼️ **Gallery Section**: Showcase your venue with an image gallery
- 🎯 **SEO Friendly**: Semantic HTML structure for better search engine optimization

## Sections

1. **Hero Section**: Eye-catching landing area with call-to-action
2. **About Section**: Information about your venue and services
3. **Gallery**: Visual showcase of your venue
4. **Services**: Detailed list of services offered
5. **Contact**: Contact form and business information
6. **Footer**: Additional links and social media

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, etc.)
- Optional: A local web server (for development)

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! The website is ready to use.

### For Development

If you want to use a local server for development:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (with http-server):**
```bash
npx http-server
```

Then open `http://localhost:8000` in your browser.

## Customization

### Colors

Edit the CSS variables in `styles.css` to change the color scheme:

```css
:root {
    --primary-color: #d4af37;    /* Main gold color */
    --secondary-color: #8b7355;  /* Secondary brown */
    --dark-color: #2c2c2c;       /* Dark text/background */
    --light-color: #f8f8f8;      /* Light background */
}
```

### Content

1. **Text Content**: Edit the HTML in `index.html`
2. **Images**: Replace placeholder images with your actual venue photos
3. **Contact Information**: Update contact details in the contact section
4. **Services**: Modify services to match your offerings

### Adding Images

Replace the placeholder divs in the gallery section with actual images:

```html
<div class="gallery-image">
    <img src="path/to/your/image.jpg" alt="Venue Image">
</div>
```

### Contact Form

The contact form currently shows an alert on submission. To connect it to a backend:

1. Update the form submission handler in `script.js`
2. Add your backend API endpoint
3. Handle form validation and submission on the server side

## File Structure

```
prabhat-celebrations/
│
├── index.html          # Main HTML file
├── styles.css          # All styles and responsive design
├── script.js           # JavaScript for interactivity
└── README.md          # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Future Enhancements

- [ ] Add image lightbox for gallery
- [ ] Integrate with backend API for contact form
- [ ] Add blog section
- [ ] Add testimonials section
- [ ] Add booking calendar
- [ ] Add multi-language support

## License

This template is free to use for your wedding venue business.

## Support

For questions or customization help, feel free to reach out!

---

**Made with ❤️ for Prabhat Celebrations**

