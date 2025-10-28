# Student Portfolio Website

A modern, responsive, and accessible personal portfolio website built with HTML, CSS, and JavaScript.

## Features

### 🎨 Design & Layout
- **Responsive Design**: Mobile-first approach with breakpoints for tablet and desktop
- **Modern UI**: Clean, professional design with smooth animations
- **Accessibility**: WCAG compliant with proper ARIA labels and keyboard navigation
- **Performance**: Optimized for fast loading and smooth interactions

### 📱 Responsive Breakpoints
- **Mobile**: < 768px (Single column layout)
- **Tablet**: 768px - 1024px (Two-column layout)
- **Desktop**: > 1024px (Multi-column layout)

### 🚀 Interactive Features
- **Smooth Scrolling Navigation**: Seamless navigation between sections
- **Mobile Hamburger Menu**: Responsive navigation for mobile devices
- **Image Carousel/Slider**: Multiple images for each project showcase
- **Form Validation**: Real-time validation for contact form
- **Scroll Animations**: Elements animate into view as you scroll
- **Scroll-to-Top Button**: Easy navigation back to top
- **Active Navigation**: Highlights current section in navigation
- **Auto-play Carousel**: Projects images automatically cycle

### ♿ Accessibility Features
- **Semantic HTML5**: Proper use of semantic elements
- **ARIA Labels**: Screen reader friendly navigation and form elements
- **Keyboard Navigation**: Full keyboard support for all interactive elements
- **Focus Management**: Clear focus indicators for keyboard users
- **Color Contrast**: WCAG AA compliant color contrast ratios
- **Skip Links**: Quick navigation to main content
- **Alt Text**: Descriptive alt attributes for all images

## File Structure

```
portfolio/
├── index.html              # Main HTML structure
├── css/
│   └── styles.css          # All styling with responsive design
├── js/
│   └── script.js           # Interactive features and animations
├── assets/
│   └── images/             # Portfolio images
│       └── placeholder.txt  # Image requirements and guidelines
└── README.md               # This file
```

## Sections

### 🏠 Home/Hero Section
- Brief introduction and navigation
- Call-to-action buttons
- Professional profile image

### 👨‍💻 About Me Section
- Personal background and education
- Academic journey and interests
- Professional image

### 🛠️ Skills Section
- Technical skills organized by category
- Programming languages, frameworks, and tools
- Interactive skill tags

### 💼 Projects Section
- Featured projects with **image carousels/sliders**
- Multiple screenshots for each project
- Technology stack for each project
- Live demo and GitHub links
- Auto-play carousel with manual controls

### 📞 Contact Section
- Contact information and social links
- Functional contact form with validation
- Multiple ways to get in touch

## Getting Started

### Prerequisites
- A modern web browser
- Basic understanding of HTML, CSS, and JavaScript

### Setup
1. Download or clone the portfolio files
2. Add your personal images to the `assets/images/` directory
3. Customize the content in `index.html` with your information
4. Open `index.html` in a web browser

### Customization

#### Personal Information
Update the following in `index.html`:
- Name and title in hero section
- About me content and education details
- Skills and technologies
- Project descriptions and links
- Contact information

#### Images
Add the following images to `assets/images/`:

**Profile & About:**
- `profile.jpg` - Your profile picture (300x300px)
- `about.jpg` - About section image (500x400px)

**Project Carousels (3 images each):**
- `project1-1.jpg`, `project1-2.jpg`, `project1-3.jpg` (600x300px each)
- `project2-1.jpg`, `project2-2.jpg`, `project2-3.jpg` (600x300px each)
- `project3-1.jpg`, `project3-2.jpg`, `project3-3.jpg` (600x300px each)

#### Using Placeholder Images (for testing)
You can use online placeholder services for development:
```html
<!-- Example for profile image -->
<img src="https://picsum.photos/300/300?random=1" alt="Profile picture">
```

#### Styling
Customize colors and fonts in `css/styles.css`:
- Update CSS custom properties in `:root` section
- Modify color scheme, typography, and spacing
- Adjust responsive breakpoints if needed

## Image Carousel Controls

### User Controls:
- **Previous/Next Buttons**: Click arrows to navigate
- **Dots**: Click on dots to jump to specific image
- **Keyboard**: Use arrow keys (← →) to navigate
- **Auto-play**: Images change automatically every 5 seconds
- **Pause**: Hover over carousel to pause auto-play

### Accessibility:
- Keyboard navigation support
- ARIA labels for screen readers
- Focus indicators for buttons

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- **Lazy Loading**: Images load as they come into view
- **Debounced Events**: Optimized scroll and resize handlers
- **CSS Custom Properties**: Efficient theming system
- **Minimal Dependencies**: No external libraries required
- **Smooth Animations**: Hardware-accelerated transitions

## Accessibility Compliance

- **WCAG 2.1 AA**: Meets accessibility guidelines
- **Screen Reader Support**: Proper ARIA labels and semantic HTML
- **Keyboard Navigation**: Full keyboard accessibility
- **Focus Management**: Clear focus indicators
- **Color Contrast**: Sufficient contrast ratios
- **Reduced Motion**: Respects prefers-reduced-motion setting

## Form Validation

The contact form includes:
- Required field validation
- Email format validation
- Name validation (letters and spaces only)
- Message length validation (minimum 10 characters)
- Real-time error messages
- Accessible error announcements

## Development

### Adding New Sections
1. Add new section to HTML with proper semantic structure
2. Style the section in CSS with responsive design
3. Add scroll animation in JavaScript if needed
4. Update navigation menu

### Adding New Projects
1. Copy existing project card structure
2. Update carousel with 3 images for the new project
3. Update content, descriptions, and links
4. Add appropriate technology tags
5. Test carousel functionality

### Customizing Carousel
To adjust carousel settings in `js/script.js`:
```javascript
// Change auto-play speed (default 5000ms = 5 seconds)
autoPlayInterval = setInterval(nextSlide, 5000);
```

## Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually main)
4. Access your portfolio at `https://username.github.io/repository-name`

### Netlify
1. Connect your GitHub repository to Netlify
2. Set build command (none needed for static site)
3. Set publish directory to root
4. Deploy automatically on git push

### Vercel
1. Import GitHub repository to Vercel
2. Configure build settings (no build needed)
3. Deploy with automatic updates

## Troubleshooting

### Images not loading
- Check file paths in `index.html`
- Ensure images are in `assets/images/` directory
- Verify image file names match exactly
- Use placeholder images for testing

### Carousel not working
- Check browser console for JavaScript errors
- Ensure all carousel images have correct class names
- Verify carousel buttons have correct data attributes
- Test with browser developer tools

### Mobile menu not opening
- Check that hamburger and nav-menu IDs are correct
- Verify JavaScript is loaded after HTML
- Test in responsive design mode

## License

This portfolio template is free to use for personal and educational purposes.

## Support

For questions or issues:
- Check the code comments for implementation details
- Test in multiple browsers and devices
- Validate HTML and CSS for errors
- Ensure all images are properly optimized

---

**Built with ❤️ using HTML, CSS, and JavaScript**
