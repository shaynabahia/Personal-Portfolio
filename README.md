# Shayna Bahia - Personal Portfolio Website

A beautiful, modern, and responsive personal portfolio website showcasing projects and skills with a stunning design featuring your favorite colors (pink, blue, green).

## 🌟 Features

### Design & Visual
- **Modern Gradient Design**: Beautiful gradients using your favorite colors (pink, blue, green)
- **Responsive Layout**: Fully responsive design that works on all devices
- **Smooth Animations**: Elegant animations and transitions throughout
- **Interactive Elements**: Hover effects, parallax scrolling, and dynamic interactions
- **Custom Scrollbar**: Styled scrollbar matching the color scheme

### Sections
- **Hero Section**: Eye-catching introduction with animated floating shapes
- **About Section**: Personal information and skills showcase
- **Projects Section**: Featured projects including Budget Tracker Pro
- **Contact Section**: Contact form and social media links

### Functionality
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Seamless navigation between sections
- **Contact Form**: Functional contact form with validation
- **Notification System**: Success/error notifications for form submissions
- **Scroll to Top**: Convenient button to return to the top
- **Loading Animations**: Smooth page load and element animations

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- No additional dependencies required (uses CDN for fonts and icons)

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. The website is ready to use!

### File Structure
```
Shayna-Bahia-Website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization

### Colors
The website uses CSS custom properties (variables) for easy color customization. Main colors are defined in `styles.css`:

```css
:root {
    --primary-pink: #ff6b9d;
    --secondary-pink: #ff8fab;
    --primary-blue: #4ecdc4;
    --secondary-blue: #45b7aa;
    --primary-green: #95e1d3;
    --secondary-green: #81c7bb;
    --accent-purple: #a8a4e6;
    --accent-orange: #ffa726;
}
```

### Content Updates
- **Personal Information**: Update the hero section, about section, and contact information in `index.html`
- **Projects**: Add or modify projects in the projects section
- **Skills**: Update the skills and technologies in the about section
- **Contact Details**: Modify email, phone, and social media links

### Adding New Projects
To add a new project, copy this structure in the projects section:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">
            <i class="fas fa-[icon-name]"></i>
        </div>
    </div>
    <div class="project-content">
        <h3 class="project-title">Project Name</h3>
        <p class="project-description">Project description here...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link">
                <i class="fas fa-external-link-alt"></i>
                Live Demo
            </a>
            <a href="#" class="project-link">
                <i class="fab fa-github"></i>
                Code
            </a>
        </div>
    </div>
</div>
```

## 📱 Responsive Design

The website is fully responsive and optimized for:
- **Desktop**: Full layout with side-by-side sections
- **Tablet**: Adjusted grid layouts and spacing
- **Mobile**: Single-column layout with mobile navigation

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📧 Contact Form

The contact form includes:
- Form validation
- Email format checking
- Success/error notifications
- Simulated submission (ready for backend integration)

To connect to a real backend, modify the form submission handler in `script.js`.

## 🚀 Deployment

The website can be deployed to any static hosting service:

- **GitHub Pages**: Push to a GitHub repository and enable Pages
- **Netlify**: Drag and drop the folder to Netlify
- **Vercel**: Connect your repository to Vercel
- **Any web server**: Upload files to any web hosting service

## 🔧 Advanced Customization

### Adding Custom Fonts
Replace the Google Fonts link in `index.html` with your preferred font:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

### Modifying Animations
Animation speeds and effects can be adjusted in `styles.css` and `script.js`.

### Adding More Sections
The modular structure makes it easy to add new sections following the existing pattern.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

---

**Created with ❤️ for Shayna Bahia**

*This portfolio showcases modern web development skills and provides a beautiful platform to display your work and connect with potential clients or employers.* 