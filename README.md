# Chinmaya Vidyalaya Website

A modern, responsive website for Chinmaya Vidyalaya schools, inspired by the original Chinmaya Vidyalaya Banashankari website. This website features a clean design, smooth animations, and comprehensive content management.

## Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Hero Carousel**: Auto-advancing slides with navigation controls
- **Interactive Navigation**: Dropdown menus and smooth scrolling
- **Contact Form**: Functional contact form with validation
- **Testimonials**: Parent testimonials section
- **Events Gallery**: Latest events and news display
- **Management Team**: Leadership team showcase
- **Programs**: Pre-Primary, Primary, and Secondary education programs
- **Accessibility**: Keyboard navigation and focus management
- **Performance Optimized**: Lazy loading and debounced scroll events

## File Structure

```
chinmaya-vidyalaya-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Getting Started

1. **Download the files**: Save all files in the same directory
2. **Open in browser**: Double-click `index.html` to open in your web browser
3. **Customize content**: Edit the HTML file to update text, images, and contact information
4. **Modify styling**: Update `styles.css` to change colors, fonts, and layout
5. **Add functionality**: Extend `script.js` for additional features

## Customization Guide

### 1. Updating School Information

**Contact Details** (in `index.html`):
```html
<!-- Update phone numbers -->
<i class="fas fa-phone"></i> +91 YOUR-PHONE-NUMBER

<!-- Update email -->
<i class="fas fa-envelope ms-3"></i> your-email@domain.com

<!-- Update address -->
<p class="mb-4">Your School Address Here</p>
```

**School Name and Logo**:
```html
<!-- Update school name -->
<span class="ms-2">Your School Name</span>

<!-- Update logo (replace placeholder URL) -->
<img src="path/to/your/logo.png" alt="Your School" class="logo">
```

### 2. Changing Colors

Update the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #ff6b35;      /* Orange/Saffron */
    --secondary-color: #4a90e2;    /* Blue */
    --accent-color: #50c878;       /* Green */
    --dark-color: #2c3e50;         /* Dark Gray */
    --light-color: #f8f9fa;        /* Light Gray */
}
```

### 3. Adding Real Images

Replace placeholder images with actual photos:
```html
<!-- Replace placeholder URLs with actual image paths -->
<img src="images/school-building.jpg" alt="School Building">
<img src="images/management/principal.jpg" alt="Principal">
<img src="images/events/sports-day.jpg" alt="Sports Day">
```

### 4. Updating Content Sections

**Hero Section**:
```html
<h1 class="hero-title">Your Custom Title</h1>
<p class="hero-subtitle">Your custom description</p>
```

**About Section**:
```html
<h2 class="section-title">About Your School</h2>
<p class="lead">Your school description here...</p>
```

**Programs**:
```html
<h5 class="card-title">Your Program Name</h5>
<p class="card-text">Your program description...</p>
```

### 5. Adding New Sections

To add a new section, follow this template:
```html
<section id="new-section" class="py-5">
    <div class="container">
        <h2 class="section-title text-center mb-5">Section Title</h2>
        <div class="row">
            <!-- Your content here -->
        </div>
    </div>
</section>
```

## Advanced Customization

### Adding New Pages

1. Create a new HTML file (e.g., `about.html`)
2. Copy the header and footer from `index.html`
3. Add your content in between
4. Update navigation links to point to the new page

### Integrating with Backend

To make the contact form functional:
1. Set up a backend server (PHP, Node.js, Python, etc.)
2. Update the form action in `index.html`
3. Handle form submission on the server side
4. Send email notifications or save to database

### Adding More Interactive Features

**Image Gallery**:
```html
<div class="gallery">
    <img src="image1.jpg" alt="Gallery Image" onclick="openModal(this)">
    <img src="image2.jpg" alt="Gallery Image" onclick="openModal(this)">
</div>
```

**News/Blog Section**:
```html
<article class="news-article">
    <h3>Article Title</h3>
    <p class="date">Posted on: Date</p>
    <p>Article content...</p>
</article>
```

## SEO Optimization

1. **Add meta tags**:
```html
<meta name="description" content="Your school description">
<meta name="keywords" content="school, education, chinmaya, vidyalaya">
<meta name="author" content="Your School Name">
```

2. **Add structured data**:
```html
<script type="application/ld+json">
{
    "@context": "https://schema.org",
    "@type": "School",
    "name": "Your School Name",
    "address": "Your Address",
    "telephone": "Your Phone"
}
</script>
```

3. **Optimize images**: Use compressed images and add alt text
4. **Add sitemap.xml** for better search engine indexing

## Performance Optimization

1. **Compress images**: Use tools like TinyPNG or ImageOptim
2. **Minify CSS/JS**: Use online minifiers for production
3. **Enable caching**: Add cache headers if using a web server
4. **Use CDN**: Consider using a CDN for faster loading

## Browser Compatibility

This website is compatible with:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Deployment Options

### 1. GitHub Pages (Free)
1. Create a GitHub repository
2. Upload your files
3. Enable GitHub Pages in repository settings
4. Your site will be available at `username.github.io/repository-name`

### 2. Netlify (Free)
1. Sign up at netlify.com
2. Drag and drop your files
3. Get instant deployment with custom domain support

### 3. Traditional Web Hosting
1. Purchase hosting from providers like Hostinger, Bluehost, etc.
2. Upload files via FTP
3. Configure domain and SSL

### 4. Firebase Hosting (Free)
1. Install Firebase CLI
2. Initialize Firebase project
3. Deploy with `firebase deploy`

## Maintenance

1. **Regular Updates**: Keep content current (events, news, contact info)
2. **Security**: If using backend, keep server software updated
3. **Backup**: Regularly backup your website files
4. **Monitor**: Use Google Analytics to track website performance
5. **Test**: Regularly test on different devices and browsers

## Support

For customization help or technical issues:
1. Check browser console for JavaScript errors
2. Validate HTML/CSS using online validators
3. Test on different devices and browsers
4. Consider hiring a web developer for complex customizations

## License

This website template is provided as-is for educational institutions. Feel free to modify and use according to your needs.

## Credits

- **Bootstrap**: CSS framework for responsive design
- **Font Awesome**: Icons
- **Google Fonts**: Poppins font family
- **Placeholder Images**: via.placeholder.com (replace with actual images)

---

**Note**: Remember to replace all placeholder content, images, and contact information with your actual school details before going live.