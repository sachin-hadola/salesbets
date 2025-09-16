# SalesBets - Sports Betting Website

A modern, responsive landing page for SalesBets, a revolutionary "no-risk" sports betting platform that focuses on athlete performance predictions without traditional financial risk.

## Project Overview

SalesBets presents itself as a futuristic sports betting platform where users can make predictions on athlete performance goals without losing money. The website features a sleek, modern design with smooth animations and responsive layouts.

## Key Features

- **Responsive Design**: Fully responsive across desktop, tablet, and mobile devices
- **Modern UI/UX**: Contemporary design with gradient backgrounds, glassmorphism effects, and smooth animations
- **Interactive Elements**: Hover effects, scroll-triggered animations, and dynamic counters
- **Multi-page Navigation**: Navigation structure suggests multiple pages (Athletes, Teams, Apps, etc.)
- **Performance Optimized**: Lightweight design with efficient CSS animations

## Technology Stack

### Frontend
- **HTML5**: Semantic markup with proper structure
- **CSS3**: Custom properties, flexbox, grid, animations, and modern styling techniques
- **JavaScript (ES6+)**: DOM manipulation, scroll effects, and interactive features
- **Bootstrap 5.3.2**: Responsive grid system and components

### External Dependencies
- **Bootstrap CSS/JS**: `cdn.jsdelivr.net/npm/bootstrap@5.3.2`
- **Font Awesome 6.4.0**: Icons (`cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0`)
- **Google Fonts**: Inter and Poppins font families

### Assets Used
- **Placeholder Images**: 
  - Athlete photos from `randomuser.me` API
  - Team logos from `dummyimage.com` service
- **Icons**: Font Awesome icon set
- **Fonts**: Google Fonts (Inter for body text, Poppins for headings)

## Project Structure

Based on the navigation and links in the HTML, the complete website appears to have these pages:
```
├── index.html (provided)
├── athletes.html
├── ownership.html
├── teams.html
├── apps.html
├── contact.html
└── assets/
    └── (images, additional CSS/JS files)
```

## Design Assumptions

1. **Target Audience**: Sports enthusiasts and betting-curious users seeking risk-free entertainment
2. **Platform Focus**: Multi-sport coverage with emphasis on performance metrics
3. **Business Model**: Appears to focus on engagement and rewards rather than traditional gambling
4. **User Experience**: Emphasis on trust-building through "no-risk" messaging
5. **Scalability**: Design suggests plans for mobile apps and team-specific content

## Color Scheme & Branding

- **Primary Colors**: 
  - Indigo (`#6366f1`) and Purple (`#8b5cf6`) gradients
  - Green accent (`#10b981`) for success states
  - Amber (`#f59e0b`) for highlights
- **Typography**: 
  - Headings: Poppins (bold, modern)
  - Body text: Inter (clean, readable)
- **Visual Style**: Modern glassmorphism with gradients and subtle shadows

## Installation & Local Setup

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional but recommended)

### Quick Start

1. **Clone or Download**
   ```bash
   # If using Git
   git clone git@github.com:sachin-hadola/salesbets.git
   cd salesbets
   
   # Or download and extract ZIP file from email
   ```

2. **Folder Description**
   ```
     There are 2 folder inside "salesbets" foldder:
     1. salesbets-prototype
     2. nsblpa-prototype
   ```

3. **Access Website**
   ```
   Open browser and navigate to:
   http://localhost/salesbets/salesbets-prototype
   http://localhost/salesbets/nsblpa-prototype
   ```

3. **Website URL for testing**
   ```
     https://sachin-hadola.github.io/salesbets/salesbets-prototype
     https://sachin-hadola.github.io/salesbets/nsblpa-prototype
   ```

## Browser Compatibility

- **Modern Browsers**: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- **CSS Features Used**: CSS Grid, Flexbox, Custom Properties, Backdrop Filter
- **JavaScript Features**: ES6+ syntax, Intersection Observer API

## Performance Considerations

### Optimizations Included
- Efficient CSS animations with `transform` and `opacity`
- Intersection Observer for scroll-triggered animations
- Responsive images and appropriate image formats
- Minified external dependencies via CDN

### Potential Improvements
- **Image Optimization**: Replace placeholder images with optimized WebP formats
- **CSS/JS Minification**: Minify custom CSS and JavaScript
- **Critical CSS**: Inline critical CSS for faster initial paint
- **Lazy Loading**: Implement lazy loading for below-fold images
- **Service Worker**: Add offline functionality and caching

## Development Notes

### JavaScript Functionality
- **Navbar Scroll Effect**: Changes navbar appearance on scroll
- **Fade-in Animations**: Uses Intersection Observer for smooth reveal animations
- **Counter Animation**: Animated statistics counters in hero section
- **Newsletter Form**: Basic form interaction with validation
- **Smooth Scrolling**: Enhanced navigation experience

### Responsive Breakpoints
- **Mobile**: < 576px
- **Tablet**: 576px - 768px  
- **Desktop**: 768px - 992px
- **Large Desktop**: > 992px

### CSS Architecture
- **CSS Custom Properties**: Consistent color and spacing system
- **Component-based Styling**: Modular CSS approach
- **Mobile-first**: Responsive design methodology
- **Animation Performance**: Hardware-accelerated animations

## Content Warnings

**Note**: This website promotes a betting/gambling-adjacent platform. While marketed as "no-risk," users should be aware that any form of betting or prediction-based gaming can potentially develop into problematic behaviors. The platform's business model and regulatory compliance are unclear from the provided materials.
