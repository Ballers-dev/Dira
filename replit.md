# Daira Public Health Consulting Website

## Overview

This is a static informational website for Daira Public Health Policy and Practice, a registered Canadian public health consultancy led by Dr. Anis Kazi. The website serves as a professional showcase for the consultancy's services, including policy analysis, health systems assessment, and health communications. Built with vanilla HTML, CSS, and minimal JavaScript, the site focuses on clean design, professional presentation, and accessibility while maintaining a modern, healthcare-appropriate aesthetic.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Technology Stack**: Pure HTML5, CSS3, and vanilla JavaScript - no frameworks or libraries
- **Design Pattern**: Multi-page static site architecture with shared navigation and consistent styling
- **Responsive Design**: Mobile-first CSS approach with breakpoints for tablets and desktops
- **Navigation**: Sticky header navigation with hamburger menu for mobile devices
- **Typography**: Google Fonts integration (Lato family) for professional, accessible text rendering

### Page Structure
- **Home Page (index.html)**: Hero section with mission statement and call-to-action
- **About Page (about.html)**: Company background and Dr. Kazi's professional profile
- **Services Page (services.html)**: Grid layout of consulting services with inquiry buttons
- **Contact Page (contact.html)**: Contact form and professional contact information

### Styling Architecture
- **CSS Organization**: Single stylesheet (styles.css) with logical sectioning
- **Color Scheme**: Professional palette using whites, light neutrals, and soft blues/greens
- **Layout Strategy**: Container-based layouts with generous whitespace and padding
- **Interactive Elements**: Hover effects, smooth scrolling, and mobile menu animations

### JavaScript Functionality
- **Mobile Navigation**: Toggle functionality for responsive burger menu
- **Scroll Effects**: Dynamic navbar styling based on scroll position
- **Smooth Scrolling**: Enhanced user experience for anchor link navigation
- **Click Outside**: Auto-close mobile menu when clicking outside navigation area

## External Dependencies

### Third-Party Services
- **Google Fonts API**: Lato font family loading with preconnect optimization for performance
- **Font Loading Strategy**: Preconnect to fonts.googleapis.com and fonts.gstatic.com for faster font delivery

### Browser Compatibility
- **HTML5**: Semantic markup with proper meta tags for SEO and accessibility
- **CSS3**: Modern CSS features with fallbacks for older browsers
- **JavaScript**: ES6+ features with DOM manipulation for enhanced interactivity

### Performance Optimizations
- **Font Loading**: Preconnect directives and display=swap for optimal font rendering
- **Minimal Dependencies**: No external JavaScript frameworks or CSS libraries to reduce bundle size
- **Semantic HTML**: Proper document structure for better SEO and accessibility compliance