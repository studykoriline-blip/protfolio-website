# Alex Chen - Personal Portfolio Website

A stunning, production-grade personal portfolio website built with HTML, CSS, and vanilla JavaScript. Features a dark luxury theme with neon accents, smooth animations, and a modern editorial design aesthetic.

## Features

### Design & Aesthetics
- **Dark Luxury Theme**: Deep navy/charcoal background with electric cyan and amber accents
- **Typography**: Playfair Display (headings) and DM Sans (body) from Google Fonts
- **Glass-morphism**: Frosted glass effects with backdrop filters
- **Particle Effects**: Animated background particles in hero section
- **Grain Texture**: Subtle texture overlay for depth
- **Responsive Design**: Mobile-first approach with tablet and desktop breakpoints

### Sections
1. **Hero Section**: Full-screen with animated background, typewriter effect, and CTA buttons
2. **About Section**: Two-column layout with photo, bio, and tech stack tags
3. **Skills Section**: Categorized skills with animated progress bars and icon cards
4. **Projects Section**: Filterable grid with hover overlays and project details
5. **Experience Timeline**: Vertical timeline with alternating layout
6. **Contact Section**: Contact form with validation and social links
7. **Footer**: Minimal footer with navigation links

### Interactive Features
- **Loading Screen**: Animated logo and loading bar (2.5 seconds)
- **Smooth Scrolling**: Navigation with active link highlighting
- **Mobile Menu**: Hamburger menu with smooth animations
- **Scroll Animations**: IntersectionObserver for fade-in effects
- **Project Filters**: Dynamic filtering by category (All/Web/App/Design)
- **Contact Form**: Client-side validation with toast notifications
- **Typewriter Effect**: Rotating text animation in hero section
- **Skill Bars**: Animated progress bars on scroll
- **Parallax Effects**: Subtle parallax on hero background

## Technical Implementation

### Technologies Used
- **HTML5**: Semantic markup with proper structure
- **CSS3**: Modern features including Grid, Flexbox, Custom Properties, and animations
- **Vanilla JavaScript**: ES6+ features with no external dependencies
- **Font Awesome**: Icon library for social links and UI elements
- **Google Fonts**: Playfair Display and DM Sans

### Key Features
- **CSS Custom Properties**: Centralized theming and easy customization
- **IntersectionObserver API**: Performance-optimized scroll animations
- **Debouncing**: Optimized scroll event handlers
- **Responsive Images**: Proper image handling with fallbacks
- **Accessibility**: Semantic HTML and keyboard navigation
- **Performance**: Optimized animations and efficient JavaScript

### Browser Compatibility
- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome Mobile)

## File Structure

```
portfolio-website/
|-- index.html          # Main HTML file
|-- styles.css          # Complete styling with animations
|-- script.js           # All JavaScript functionality
|-- README.md           # Project documentation
```

## Customization

### Colors
Edit the CSS custom properties in `:root`:
```css
:root {
    --primary-color: #00d4ff;      /* Electric cyan */
    --secondary-color: #ff6b35;    /* Amber accent */
    --bg-primary: #0a0e27;         /* Dark navy */
    --bg-secondary: #151932;       /* Charcoal */
    /* ... other variables */
}
```

### Content
Update the following in `index.html`:
- Name and title in hero section
- About section content
- Skills and proficiency levels
- Project details and links
- Experience timeline
- Contact information

### Fonts
Change Google Fonts imports in `<head>`:
```html
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700;900&family=DM+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

## Deployment

### Local Development
1. Open `index.html` in a web browser
2. No build process required - works immediately

### Production Deployment
1. Upload all files to your web server
2. Ensure server supports static file hosting
3. Update any absolute paths if needed

### GitHub Pages
1. Push files to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main` or `gh-pages`)

## Performance Notes

- **Optimized Animations**: Uses CSS transforms and opacity for better performance
- **Lazy Loading**: Images load as needed
- **Debounced Events**: Scroll handlers are debounced to prevent performance issues
- **Efficient JavaScript**: Uses modern APIs and best practices

## Accessibility Features

- Semantic HTML5 structure
- Keyboard navigation support
- Focus states for interactive elements
- Screen reader friendly markup
- High contrast design

## Browser DevTools Tips

Open browser DevTools to:
- Inspect animations and transitions
- Test responsive design with device simulation
- Monitor performance in the Performance tab
- Debug JavaScript in the Console tab

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Created with passion by Alex Chen**  
*Full-Stack Developer & UI Designer*

## Getting Started

1. Clone or download the files
2. Open `index.html` in your preferred web browser
3. Customize the content to match your information
4. Deploy to your preferred hosting platform

Enjoy your stunning new portfolio website!
