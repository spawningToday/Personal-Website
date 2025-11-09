# Personal Website

A clean and modern personal website template built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Multiple Sections**: 
  - Home/Hero section with introduction
  - About section for personal information
  - Skills section to showcase your abilities
  - Projects section to display your work
  - Contact section with social links
- **Interactive Navigation**: Smooth scrolling and mobile-friendly hamburger menu
- **Easy to Customize**: Simple HTML structure with well-commented code

## Getting Started

1. **Clone or download this repository**
2. **Customize the content**:
   - Open `index.html` and replace placeholder text with your own information
   - Update "Your Name" with your actual name
   - Add your email address and social media links
   - Modify the skills and projects sections with your own details
3. **Customize the styling** (optional):
   - Edit `styles.css` to change colors, fonts, or layout
   - The CSS uses CSS variables at the top for easy color customization
4. **Open `index.html` in your browser** to view your website

## File Structure

```
Personal-Website/
├── index.html      # Main HTML file with website structure
├── styles.css      # CSS file with all styling
├── script.js       # JavaScript file for interactivity
└── README.md       # This file
```

## Customization Tips

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #3498db;    /* Main brand color */
    --secondary-color: #2c3e50;  /* Secondary color */
    --text-color: #333;          /* Text color */
    /* ... */
}
```

### Adding New Projects
Copy and paste a project card in the projects section of `index.html`:
```html
<div class="project-card">
    <h3>Your Project Name</h3>
    <p>Project description...</p>
    <div class="project-links">
        <a href="#" class="btn btn-secondary">View Demo</a>
        <a href="#" class="btn btn-secondary">Source Code</a>
    </div>
</div>
```

### Modifying Skills
Update the skills section in `index.html` with your own technologies and tools.

## Deployment

You can deploy this website to:
- **GitHub Pages**: Push to a GitHub repository and enable GitHub Pages in settings
- **Netlify**: Drag and drop the folder to Netlify for instant deployment
- **Vercel**: Connect your repository for automatic deployments
- **Any web hosting service**: Upload all files to your hosting provider

## Browser Support

This website works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## License

Feel free to use this template for your personal website. No attribution required.

## Contributing

If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.