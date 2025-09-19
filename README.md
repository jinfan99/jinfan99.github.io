# Personal Homepage

A modern, responsive personal homepage inspired by academic and professional websites. Built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Navigation**: Smooth scrolling and active link highlighting
- **Multiple Sections**: Home, About, Research, Projects, Blog, and Contact
- **Mobile-Friendly**: Hamburger menu for mobile navigation
- **Performance Optimized**: Debounced scroll events and efficient animations

## Customization Guide

### 1. Personal Information

Edit the following in `index.html`:

- **Name**: Replace "Your Name" throughout the file
- **Title**: Update your professional title and institution
- **Bio**: Customize the about section with your background
- **Contact Info**: Update email, social media links
- **Profile Image**: Replace the placeholder with your actual photo

### 2. Research Section

Add your research papers by duplicating the `.research-item` structure:

```html
<article class="research-item">
    <div class="research-image">
        <div class="placeholder-image">
            <i class="fas fa-file-alt"></i>
        </div>
    </div>
    <div class="research-content">
        <h3 class="research-title">Your Paper Title</h3>
        <p class="research-authors">Your Name, Co-authors</p>
        <p class="research-venue">Conference/Journal 2024</p>
        <p class="research-abstract">Paper description...</p>
        <div class="research-links">
            <a href="#" class="research-link">Paper</a>
            <a href="#" class="research-link">Code</a>
            <a href="#" class="research-link">Abstract</a>
        </div>
    </div>
</article>
```

### 3. Projects Section

Add your projects by duplicating the `.project-item` structure:

```html
<div class="project-item">
    <div class="project-image">
        <div class="placeholder-image">
            <i class="fas fa-code"></i>
        </div>
    </div>
    <div class="project-content">
        <h3 class="project-title">Project Name</h3>
        <p class="project-description">Project description...</p>
        <div class="project-links">
            <a href="#" class="project-link">Live Demo</a>
            <a href="#" class="project-link">GitHub</a>
        </div>
    </div>
</div>
```

### 4. Blog Section

Add blog posts by duplicating the `.blog-item` structure:

```html
<article class="blog-item">
    <div class="blog-image">
        <div class="placeholder-image">
            <i class="fas fa-blog"></i>
        </div>
    </div>
    <div class="blog-content">
        <h3 class="blog-title">Blog Post Title</h3>
        <p class="blog-date">January 15, 2024</p>
        <p class="blog-excerpt">Post excerpt...</p>
        <a href="#" class="blog-link">Read More</a>
    </div>
</article>
```

### 5. Styling Customization

Key CSS variables you can modify in `styles.css`:

- **Colors**: Update the gradient colors in the hero section
- **Fonts**: Change the font family (currently using Inter)
- **Spacing**: Adjust padding and margins
- **Animations**: Modify transition durations and effects

### 6. Adding Images

Replace placeholder images by:

1. Adding your images to an `images/` folder
2. Updating the `src` attributes in the HTML
3. Or using CSS background images

Example:
```html
<div class="research-image">
    <img src="images/paper-thumbnail.jpg" alt="Paper thumbnail">
</div>
```

### 7. Social Media Links

Update the contact section with your social media profiles:

```html
<a href="https://github.com/yourusername" class="contact-link">
    <i class="fab fa-github"></i>
    GitHub
</a>
```

## File Structure

```
homepage/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Optimized images and animations
- Debounced scroll events
- Efficient CSS animations
- Minimal JavaScript footprint

## Deployment

You can deploy this homepage to:

- **GitHub Pages**: Push to a GitHub repository and enable Pages
- **Netlify**: Drag and drop the folder to Netlify
- **Vercel**: Connect your GitHub repository
- **Any web hosting service**: Upload the files via FTP

## License

This template is free to use for personal and commercial projects.

## Credits

- Fonts: [Google Fonts](https://fonts.google.com/)
- Icons: [Font Awesome](https://fontawesome.com/)
- Inspiration: Academic and professional websites
