# SUPMTI Meknès - Modern Website Project

## 📋 Project Overview

This is a complete, modern, single-page website for **SUPMTI Meknès** (École Supérieure de Management, Télécommunication et Informatique). The website features a professional design with smooth animations, full responsiveness, and interactive elements.

---

## 🚀 Features

### Core Technologies Used
- ✅ **HTML5** - Semantic markup and structure
- ✅ **CSS3** - Modern styling with custom properties and gradients
- ✅ **JavaScript** - Dynamic interactions and animations
- ✅ **jQuery** - DOM manipulation and event handling
- ✅ **Bootstrap 5** - Responsive grid system and components
- ✅ **Animate.css** - Entrance animations on scroll
- ✅ **Hover.css** - Interactive hover effects
- ✅ **Font Awesome** - Professional icon library

### Website Sections

1. **Header & Navigation**
   - Sticky navigation bar
   - Smooth scroll to sections
   - Active link highlighting
   - Mobile-responsive hamburger menu

2. **Hero Section**
   - Bootstrap carousel with 3 slides
   - Overlay effects and captions
   - Call-to-action buttons
   - Parallax scrolling effect

3. **Statistics Section**
   - Animated counters
   - Icon-based stat cards
   - Hover animations
   - 3 key metrics: Filières, Lauréats, Nationalités

4. **Formations Section**
   - 6 program cards with details
   - Feature lists with checkmarks
   - Hover effects (grow shadow)
   - Icons for each program

5. **Feedbacks Section**
   - Student testimonial carousel
   - Star ratings
   - Student photos and info
   - Multiple testimonial slides

6. **Coopérations Section**
   - Partner logo grid
   - Grayscale to color on hover
   - 8 partner logos
   - Responsive layout

7. **Footer**
   - Contact information
   - Quick links
   - Social media icons
   - Copyright information

### Interactive Features

- 📊 **Animated Counters** - Statistics count up on scroll
- 🎨 **Scroll Animations** - Elements fade in as you scroll
- 🔼 **Scroll-to-Top Button** - Quick navigation to top
- 📱 **Fully Responsive** - Works on mobile, tablet, and desktop
- 🎯 **Active Navigation** - Highlights current section
- ⌨️ **Keyboard Navigation** - Arrow keys control carousel
- 🎉 **Easter Egg** - Konami code hidden feature

---

## 📁 Project Structure

```
SUPMTI-Website/
│
├── supmti-website.html    # Main HTML file
├── styles.css              # Custom CSS stylesheet
├── script.js               # JavaScript functionality
└── README.md               # This file
```

---

## 🛠️ Installation & Setup

### Option 1: Quick Start (Recommended)

1. **Download all files** to a folder on your computer
2. **Open `supmti-website.html`** in any modern web browser
3. That's it! The website is fully functional

### Option 2: Local Web Server

For better testing and development:

```bash
# Using Python 3
python -m http.server 8000

# Using PHP
php -S localhost:8000

# Using Node.js (install http-server first)
npx http-server
```

Then open `http://localhost:8000/supmti-website.html` in your browser.

---

## 🎨 Customization Guide

### Colors

The website uses CSS custom properties for easy customization. Edit these in `styles.css`:

```css
:root {
    --primary-color: #1e3a8a;      /* Main blue */
    --secondary-color: #3b82f6;    /* Light blue */
    --accent-color: #fbbf24;       /* Gold/yellow */
    --dark-color: #1f2937;         /* Dark gray */
    --light-color: #f8fafc;        /* Light gray */
}
```

### Images

Replace carousel images in the HTML file:

```html
<!-- Find these lines and replace the image URLs -->
<img src="YOUR_IMAGE_URL_HERE" class="d-block w-100" alt="Description">
```

### Content

All text content can be edited directly in `supmti-website.html`. Look for:
- Section titles: `<h2 class="section-title">Your Title</h2>`
- Descriptions: `<p class="section-subtitle">Your description</p>`
- Card content: Inside `.formation-card`, `.feedback-card`, etc.

### Statistics

Update the counter values in `supmti-website.html`:

```html
<h3 class="counter" data-target="15">0</h3>  <!-- Change 15 to your value -->
```

---

## 📱 Responsive Breakpoints

The website is optimized for:
- 📱 **Mobile**: < 576px
- 📱 **Tablet**: 576px - 991px
- 💻 **Desktop**: 992px - 1199px
- 🖥️ **Large Desktop**: ≥ 1200px

---

## 🔧 External Libraries (CDN)

All libraries are loaded via CDN (no downloads required):

- **Bootstrap 5.3.2** - CSS & JS
- **jQuery 3.7.0** - JavaScript library
- **Animate.css 4.1.1** - Animation library
- **Hover.css 2.3.1** - Hover effects
- **Font Awesome 6.4.0** - Icons
- **Google Fonts** - Poppins & Montserrat

---

## 🎯 Browser Compatibility

Tested and working on:
- ✅ Google Chrome (Latest)
- ✅ Mozilla Firefox (Latest)
- ✅ Microsoft Edge (Latest)
- ✅ Safari (Latest)
- ✅ Opera (Latest)

---

## 📊 Performance Optimizations

- **Lazy loading** for images
- **Throttled scroll events** for better performance
- **Debounced** resize handlers
- **Intersection Observer** for scroll animations
- **Optimized animations** with CSS transforms
- **Minimal reflows** and repaints

---

## 🎓 Educational Features

Perfect for web development exams because it demonstrates:

1. **HTML5 Best Practices**
   - Semantic elements
   - Accessibility features
   - SEO-friendly structure

2. **CSS3 Techniques**
   - Flexbox and Grid
   - Custom properties (variables)
   - Gradients and shadows
   - Transitions and animations
   - Media queries

3. **JavaScript Skills**
   - DOM manipulation
   - Event handling
   - AJAX concepts (ready for API integration)
   - ES6+ features

4. **jQuery Usage**
   - Selectors and traversal
   - Effects and animations
   - Event binding
   - AJAX (extensible)

5. **Bootstrap Framework**
   - Grid system
   - Components (navbar, carousel, cards)
   - Utilities
   - Responsive design

---

## 🔄 Future Enhancements

Potential additions for extra credit:

- 📧 **Contact Form** with email integration
- 🌐 **Multi-language Support** (French/English/Arabic)
- 🔍 **Search Functionality** for programs
- 📅 **Events Calendar** integration
- 🗺️ **Google Maps** for campus location
- 💬 **Live Chat** widget
- 📰 **News/Blog Section**
- 🎥 **Video Testimonials**
- 📊 **Application Portal** integration

---

## 📝 Code Quality

- ✅ Clean, well-commented code
- ✅ Consistent naming conventions
- ✅ Modular and maintainable structure
- ✅ Follows best practices
- ✅ Accessible (WCAG guidelines)

---

## 🐛 Troubleshooting

### Issue: Animations not working
**Solution**: Make sure you're connected to the internet (CDN links need access)

### Issue: Images not loading
**Solution**: Check image URLs and internet connection

### Issue: Counters not animating
**Solution**: Scroll to the Statistics section to trigger the animation

### Issue: Mobile menu not closing
**Solution**: Click outside the menu or on a menu item

---

## 📞 Support

For questions about this project:
- Review the code comments
- Check the console for any errors
- Ensure all CDN libraries are loading

---

## 📜 License

This project is created for educational purposes as part of a Web Development exam.

---

## 🙏 Credits

- **Design & Development**: Created for SUPMTI Meknès
- **Images**: Unsplash (placeholder images)
- **Icons**: Font Awesome
- **Fonts**: Google Fonts

---

## ✨ Key Highlights for Your Exam

This project demonstrates:

1. ✅ **All required technologies** (HTML5, CSS3, JS, jQuery, Bootstrap)
2. ✅ **All required libraries** (Animate.css, Hover.css)
3. ✅ **All required sections** (7 sections as specified)
4. ✅ **Modern UI/UX** with professional design
5. ✅ **Full responsiveness** across all devices
6. ✅ **Creative animations** and interactions
7. ✅ **Clean, documented code** ready for presentation

---

**Good luck with your exam! 🎓**

---

## 📊 Quick Stats

- **Lines of HTML**: ~650+
- **Lines of CSS**: ~850+
- **Lines of JavaScript**: ~500+
- **Total Sections**: 7
- **External Libraries**: 6
- **Responsive Breakpoints**: 4
- **Animations**: 20+
- **Interactive Elements**: 30+
