# Bootstrap Advanced Portfolio

A modern, responsive portfolio website built with Bootstrap 5, SCSS, and interactive JavaScript components. This project showcases advanced web development techniques with smooth animations, progress bars, and a clean professional design.

## 🌟 Live Demo

View the live website: [https://saadabdelghaffar.github.io/bootstrap-advanced-portfolio/](https://saadabdelghaffar.github.io/bootstrap-advanced-portfolio/)

## ✨ Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: 
  - Animated progress bars for skills
  - Scroll-triggered animations using ScrollOut.js
  - Interactive portfolio gallery with lightGallery
  - Bootstrap carousel for testimonials
- **SCSS Preprocessing**: Custom SCSS with Bootstrap integration
- **Smooth Scrolling**: Spy scroll navigation with smooth transitions
- **Contact Form**: Functional contact form with validation
- **Font Awesome Icons**: Professional iconography throughout

## 🎨 Sections

- **Hero Section**: Eye-catching banner with call-to-action buttons
- **About**: Professional introduction with feature highlights
- **Skills**: Animated progress bars showing technical proficiencies
- **Services**: Service offerings with hover effects
- **Portfolio**: Filterable project gallery with lightbox functionality
- **Testimonials**: Customer feedback carousel
- **Contact**: Contact form and information

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3/SCSS**: Advanced styling with Sass preprocessing
- **Bootstrap 5**: Responsive framework
- **JavaScript**: Interactive functionality
- **Font Awesome**: Icon library
- **ScrollOut.js**: Scroll-triggered animations
- **lightGallery**: Image gallery functionality

## 📁 Project Structure

```
bootstrap-advanced-portfolio/
├── index.html              # Main HTML file
├── css/
│   ├── bootstrap.css       # Bootstrap CSS
│   ├── lightGallery.css    # Gallery styles
│   └── style.css          # Compiled custom styles
├── scss/                   # Bootstrap source files
├── sass/
│   ├── style.scss         # Main SCSS file
│   └── __variable.scss    # SCSS variables
├── js/
│   ├── bootstrap.bundle.js # Bootstrap JavaScript
│   ├── lightGallery.js    # Gallery functionality
│   ├── scrollOut.js       # Scroll animations
│   └── main.js           # Custom JavaScript
├── img/
│   ├── portfolio/         # Portfolio images
│   ├── testimonials/      # Testimonial photos
│   └── clients/          # Client logos
└── fonts/                 # Web fonts
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- A code editor (VS Code recommended)
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. Clone the repository:
```bash
git clone https://github.com/SaadAbdElGhaffar/bootstrap-advanced-portfolio.git
```

2. Navigate to the project directory:
```bash
cd bootstrap-advanced-portfolio
```

3. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

### Development

If you want to modify the SCSS files:

1. Install Sass globally:
```bash
npm install -g sass
```

2. Watch for SCSS changes:
```bash
sass --watch sass/style.scss:css/style.css
```

## 🎯 Key Features Explained

### Animated Progress Bars
- Skills section with animated progress bars
- Triggered when scrolling into view
- Smooth percentage counter animation

### Scroll Animations
- Uses ScrollOut.js for scroll-triggered animations
- Elements animate when entering viewport
- Smooth, performant animations

### Portfolio Gallery
- Filterable portfolio items
- lightGallery integration for image viewing
- Responsive grid layout

### Navigation
- Sticky navigation with Bootstrap ScrollSpy
- Smooth scroll to sections
- Active state indicators

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (576px - 767px)
- Small Mobile (<576px)

## 🎨 Customization

### Colors
Main colors can be customized in `sass/__variable.scss`:
```scss
$primary: #0d6efd;
$secondary: #6c757d;
// Add your custom colors here
```

### Typography
Font families and sizes can be modified in the main SCSS file.

### Animations
Animation timings and effects can be adjusted in `js/main.js` and CSS files.

## 📄 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## 👤 Author

**Saad Abd El Ghaffar**
- GitHub: [@SaadAbdElGhaffar](https://github.com/SaadAbdElGhaffar)
- LinkedIn: [Saad Ahmed](https://www.linkedin.com/in/saad-ahmed-683b77219/)
- Email: saadabdelghaffar639@gmail.com
## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/SaadAbdElGhaffar/bootstrap-advanced-portfolio/issues).

## ⭐ Show Your Support

Give a ⭐️ if this project helped you!


---

Built with ❤️ using Bootstrap 5 and modern web technologies.
