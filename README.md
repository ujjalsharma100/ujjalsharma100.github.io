# Ujjal Sharma - Personal Portfolio

A simple, aesthetic personal portfolio website showcasing your work at Nutanix and AI projects.

## Features

- **Clean Design**: Modern, minimalist design with smooth animations
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **No Scrolling**: Single-page layout as requested
- **Social Links**: Placeholder links for Twitter, LinkedIn, and GitHub
- **Project Showcase**: Section to display your current AI projects
- **Interactive Elements**: Hover effects and smooth transitions

## Customization Guide

### 1. Update Social Media Links

In `index.html`, replace the `#` placeholders with your actual social media URLs:

```html
<!-- Twitter -->
<a href="https://twitter.com/yourusername" class="social-link twitter">

<!-- LinkedIn -->
<a href="https://linkedin.com/in/yourusername" class="social-link linkedin">

<!-- GitHub -->
<a href="https://github.com/yourusername" class="social-link github">
```

### 2. Update Project Links

Replace the project card links with your actual project URLs:

```html
<a href="https://your-project-url.com" class="project-card">
    <div class="project-icon">
        <i class="fas fa-robot"></i>
    </div>
    <h3 class="project-title">Your Project Name</h3>
    <p class="project-description">Your project description</p>
</a>
```

### 3. Customize Content

- **About Section**: Update the paragraph in the `about-section` to reflect your personal story
- **Project Icons**: Change the Font Awesome icons in the project cards to match your projects
- **Colors**: Modify the gradient colors in `styles.css` if you want a different color scheme

### 4. Add More Projects

To add more projects, simply duplicate the project card structure:

```html
<a href="#" class="project-card">
    <div class="project-icon">
        <i class="fas fa-your-icon"></i>
    </div>
    <h3 class="project-title">New Project</h3>
    <p class="project-description">Project description</p>
</a>
```

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript for interactions
└── README.md           # This file
```

## Getting Started

1. Open `index.html` in your web browser to view the portfolio
2. Customize the content as needed
3. Update the social media and project links
4. Deploy to your preferred hosting service

## Technologies Used

- HTML5
- CSS3 (with modern features like backdrop-filter, grid, flexbox)
- Vanilla JavaScript
- Font Awesome icons
- Google Fonts (Inter)

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

The portfolio uses modern CSS features but includes fallbacks for older browsers.

## Deployment

You can deploy this portfolio to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

Simply upload the files and you're ready to go! 