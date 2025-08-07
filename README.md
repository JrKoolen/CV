# Personal Curriculum Vitae (CV) Website

A modern, responsive Curriculum Vitae website built with HTML, CSS, and JavaScript. This comprehensive CV showcases your education, projects, skills, future timeline, personality, and hobbies in a beautiful and interactive way.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Animations**: Fade-in effects and scroll-triggered animations
- **Timeline Visualization**: Beautiful timeline for future studies
- **Skill Bars**: Animated progress bars for personality traits
- **Contact Section**: Social media links and contact information

## Sections Included

1. **Hero Section**: Welcome message with call-to-action buttons
2. **Past Studies**: Your educational background and academic achievements
3. **Past Projects**: Showcase of your work with technology tags
4. **Future Timeline**: Visual timeline of planned studies and career goals
5. **Personality**: Your traits and characteristics with skill bars
6. **Hobbies**: Your interests and activities outside of work
7. **Skills**: Comprehensive technical and soft skills assessment
8. **Footer**: Contact information and social links

## Getting Started

### Prerequisites
- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation
1. Download or clone the repository
2. Open `index.html` in your web browser
3. The CV is ready to use!

### Customization

#### Personal Information
Edit the `index.html` file to update:

- **Hero Section**: Change the title, subtitle, and buttons
- **Studies**: Update your educational background, dates, and academic achievements
- **Projects**: Add your own projects with descriptions and links
- **Timeline**: Modify your future study and career plans
- **Personality**: Update your traits and skill percentages
- **Hobbies**: Add your interests and activities
- **Skills**: Update your technical and soft skills
- **Contact**: Add your social media links

#### Styling
Modify `styles.css` to customize:

- **Colors**: Change the color scheme by updating CSS variables
- **Fonts**: Replace the Inter font with your preferred font
- **Layout**: Adjust spacing, sizes, and grid layouts
- **Animations**: Modify transition effects and timing

#### Functionality
Edit `script.js` to add:

- **New Animations**: Custom scroll effects or interactions
- **Additional Features**: Contact forms, project filters, etc.
- **Analytics**: Google Analytics or other tracking

## File Structure

```
cv-website/
├── index.html          # Main HTML structure
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization Examples

### Changing Colors
In `styles.css`, find the color values and replace them:

```css
/* Primary colors */
--primary-color: #2563eb;
--secondary-color: #667eea;
--accent-color: #764ba2;
```

### Adding a New Project
In `index.html`, add a new project card:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-project-icon"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description goes here.</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Live</a>
        </div>
    </div>
</div>
```

### Updating Timeline
Modify the timeline section in `index.html`:

```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <h3>Your Study Plan</h3>
        <p class="timeline-period">2024 - 2025</p>
        <p>Description of your study plan.</p>
    </div>
</div>
```

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Performance Tips

1. **Optimize Images**: Use compressed images for better loading times
2. **Minimize CSS/JS**: Consider minifying files for production
3. **CDN Usage**: The current setup uses CDN for fonts and icons
4. **Lazy Loading**: Consider implementing lazy loading for images

## Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your branch and save

### Netlify
1. Drag and drop your folder to Netlify
2. Your site will be live instantly

### Vercel
1. Connect your GitHub repository
2. Deploy automatically on push

## Contributing

Feel free to fork this project and customize it for your needs. If you have improvements, consider sharing them!

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your CV, check out:
- HTML/CSS documentation
- JavaScript tutorials
- Web development communities

## Future Enhancements

Consider adding:
- Blog section
- Dark mode toggle
- Contact form
- Project filtering
- Testimonials section
- Downloadable resume
- Multi-language support

---

**Happy coding! 🚀** 