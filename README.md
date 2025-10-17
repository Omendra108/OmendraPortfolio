# Omendra K Upadhyay - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This website showcases skills, projects, and professional experience of an Electrical Engineering student at IIT Bhilai.

## 🚀 Live Demo
Open `index.html` in your web browser to view the portfolio.

## 📁 Project Structure

```
portfolio-website/
├── index.html              # Home page with introduction and skills
├── projects.html           # Projects showcase page
├── contact.html            # Contact information and form
├── styles.css              # Main stylesheet with responsive design
├── script.js              # JavaScript for interactive features
├── Omendra K Upadhyay.png  # Profile photo
└── README.md               # Project documentation
```

## 🎯 Features

### 🏠 **Home Page (index.html)**
- **Hero Section**: Eye-catching introduction with profile photo
- **Skills Section**: Organized display of technical skills (Hardware, Software, Tools)
- **Experience Section**: Timeline of internships (ISRO, IIT Bhilai)
- **Call-to-Action**: Buttons linking to projects and contact

### 📁 **Projects Page (projects.html)**
- **4 Professional Projects**: Data Acquisition, Computer Vision, Gunshot Detection, Boolean Solver
- **Technology Tags**: Visual indicators of technologies used
- **GitHub Links**: Direct links to code repositories
- **Interactive Cards**: Hover effects and smooth animations

### 📞 **Contact Page (contact.html)**
- **Contact Information**: Email, LinkedIn, GitHub with working links
- **Contact Form**: Functional form with validation
- **Availability Section**: Current status and interests
- **Additional Info**: Location, time zone, and languages

## 🛠️ Technical Features

### **Frontend Technologies:**
- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Modern styling with Flexbox, Grid, and animations
- **JavaScript**: Interactive features and form validation
- **Font Awesome**: Professional icons throughout the site

### **Design Features:**
- ✅ **Fully Responsive**: Mobile-first design with breakpoints
- ✅ **Modern CSS**: Flexbox, Grid, CSS animations, and gradients
- ✅ **Interactive JavaScript**: Smooth scrolling, form validation, animations
- ✅ **Accessibility**: Proper semantic HTML, keyboard navigation, focus management
- ✅ **Performance**: Optimized loading and smooth transitions
- ✅ **Cross-browser Compatible**: Works on all modern browsers

## 📱 Responsive Design

### **Breakpoints:**
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

### **Mobile Features:**
- Hamburger menu navigation
- Touch-friendly buttons and links
- Optimized typography and spacing
- Collapsible sections

## 🎨 Color Scheme

### **Primary Colors:**
- **Gradient Background**: #667eea to #764ba2
- **Text**: #333 (dark gray)
- **Accent**: #3498db (blue)
- **Success**: #27ae60 (green)

### **Background Colors:**
- **Hero Section**: Gradient background
- **Skills/Projects**: White (#fff)
- **Experience/Contact**: Light gray (#f8f9fa)
- **Footer**: Dark blue (#2c3e50)

## 🔧 Customization Guide

### **Personal Information Updates:**

#### **1. Profile Information:**
```html
<!-- Update in index.html -->
<h1>Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="hero-subtitle">Your Title</p>
```

#### **2. Contact Information:**
```html
<!-- Update in contact.html -->
<p>your.email@example.com</p>
<a href="https://linkedin.com/in/yourprofile">View Profile</a>
<a href="https://github.com/yourusername">View Repositories</a>
```

#### **3. Social Media Links:**
```html
<!-- Update in all HTML files footer -->
<a href="https://linkedin.com/in/yourprofile" class="social-link">
<a href="https://github.com/yourusername" class="social-link">
<a href="mailto:your.email@example.com" class="social-link">
```

### **Content Updates:**

#### **Skills Section:**
- Add/remove skill categories in `index.html`
- Update skill tags with your technologies
- Modify CSS classes for styling

#### **Projects Section:**
- Update project information in `projects.html`
- Add/remove project cards
- Update GitHub links and descriptions
- Change project icons (Font Awesome classes)

#### **Experience Section:**
- Update work experience in `index.html`
- Add/remove experience items
- Modify dates and descriptions

### **Styling Customization:**

#### **Colors:**
```css
/* Update in styles.css */
:root {
    --primary-color: #3498db;
    --secondary-color: #2c3e50;
    --accent-color: #f39c12;
}
```

#### **Fonts:**
```css
/* Update in styles.css */
body {
    font-family: 'Your Font', sans-serif;
}
```

#### **Layout:**
- Modify grid layouts in CSS
- Adjust spacing and padding
- Update responsive breakpoints

## 🚀 Deployment Options

### **GitHub Pages:**
1. Create a GitHub repository
2. Upload all files to the repository
3. Enable GitHub Pages in repository settings
4. Your site will be available at `username.github.io/repository-name`

### **Netlify:**
1. Drag and drop the project folder to Netlify
2. Your site will be automatically deployed
3. Custom domain can be added in settings

### **Vercel:**
1. Connect your GitHub repository to Vercel
2. Automatic deployments on every push
3. Custom domain support available

## 📋 File Descriptions

### **HTML Files:**
- **index.html**: Main landing page with hero, skills, and experience
- **projects.html**: Portfolio projects showcase
- **contact.html**: Contact information and form

### **CSS File (styles.css):**
- **Reset & Base Styles**: CSS reset and basic styling
- **Navigation**: Fixed navbar with mobile menu
- **Hero Section**: Gradient background with profile image
- **Skills Section**: Grid layout for skill categories
- **Experience Section**: Timeline layout for work experience
- **Projects Section**: Card-based project showcase
- **Contact Section**: Form and contact information styling
- **Responsive Design**: Mobile-first responsive breakpoints
- **Animations**: Smooth transitions and hover effects

### **JavaScript File (script.js):**
- **Mobile Navigation**: Hamburger menu functionality
- **Smooth Scrolling**: Anchor link navigation
- **Form Validation**: Contact form validation and submission
- **Animations**: Scroll-triggered animations
- **Interactive Features**: Hover effects and transitions

## 🔍 Code Organization

### **HTML Structure:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta tags and external resources -->
</head>
<body>
    <nav><!-- Navigation bar --></nav>
    <main>
        <!-- Main content sections -->
    </main>
    <footer><!-- Footer with social links --></footer>
    <script><!-- JavaScript functionality --></script>
</body>
</html>
```

### **CSS Organization:**
```css
/* Reset and Base Styles */
/* Navigation Styles */
/* Hero Section Styles */
/* Skills Section Styles */
/* Experience Section Styles */
/* Projects Section Styles */
/* Contact Section Styles */
/* Footer Styles */
/* Responsive Design */
/* Animations */
```

### **JavaScript Organization:**
```javascript
/* Mobile Navigation Toggle */
/* Smooth Scrolling */
/* Form Handling */
/* Animations */
/* Performance Optimizations */
```

## 🎯 Performance Features

- **Lazy Loading**: Images load as they come into view
- **Smooth Animations**: Hardware-accelerated CSS transitions
- **Optimized Assets**: Minified and compressed files
- **Fast Loading**: Minimal external dependencies
- **Caching**: Browser-friendly caching headers

## ♿ Accessibility Features

- **Semantic HTML**: Proper heading structure and landmarks
- **Keyboard Navigation**: Full keyboard accessibility
- **Screen Reader Support**: ARIA labels and descriptions
- **Focus Management**: Visible focus indicators
- **Color Contrast**: WCAG compliant color schemes
- **Alt Text**: Descriptive alt text for images

## 🐛 Troubleshooting

### **Common Issues:**

#### **1. Images Not Loading:**
- Check file paths and names
- Ensure images are in the correct directory
- Verify file permissions

#### **2. Styling Issues:**
- Check CSS file is linked correctly
- Verify class names match HTML
- Clear browser cache

#### **3. JavaScript Not Working:**
- Check browser console for errors
- Verify script.js is linked correctly
- Ensure DOM is loaded before script execution

#### **4. Mobile Menu Not Working:**
- Check JavaScript console for errors
- Verify hamburger menu HTML structure
- Test on different devices

## 📞 Support

For questions or issues:
- Check the browser console for JavaScript errors
- Validate HTML and CSS for syntax errors
- Test on different devices and browsers
- Ensure all file paths are correct

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- **Font Awesome**: For the beautiful icons
- **CSS Grid & Flexbox**: For modern layout capabilities
- **IIT Bhilai**: For the educational foundation
- **ISRO**: For the internship opportunity

---

**Note**: Remember to replace all placeholder content with your actual information before deploying your portfolio website.

**Last Updated**: January 2025
**Version**: 1.0.0#   O m e n d r a P o r t f o l i o  
 