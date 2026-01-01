# Golden Cup Exim Marketing Corporation Website

A modern, responsive website for Golden Cup Exim Marketing Corporation - a trusted leader in copier solutions and rentals in the Philippines with over 30 years of experience.

## Overview

This website showcases Golden Cup's services including copier rentals, sales, maintenance, and consumables. The site is designed to help businesses, schools, and agencies find affordable and reliable copier solutions.

## Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Hero Section**: Eye-catching hero section with a quote request form
- **Services Showcase**: Display of four main services (Rental, Sales, Consumables & Parts, Maintenance & Service)
- **Problem-Solution Section**: Highlights common issues and how Golden Cup addresses them
- **About Us**: Company information and image carousel
- **Contact Information**: Complete contact details including address, phone, email, and social media links
- **Smooth Navigation**: Sticky navbar with smooth scrolling and active link highlighting
- **Interactive Carousel**: Image carousel in the About Us section with navigation controls

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with modern design
- **JavaScript (ES6+)**: Interactive functionality
- **Bootstrap 5.3.2**: Responsive framework and components
- **Font Awesome 6.4.0**: Icons

## Project Structure

```
goldencupemc/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css       # Custom styles
│   ├── js/
│   │   └── script.js       # JavaScript functionality
│   └── img/                # Images and logos
│       ├── GOLDEN-CUP-LOGO-Fixed-280-px.png
│       ├── Our-services-*.png
│       └── ...
└── README.md               # This file
```

## Getting Started

### Prerequisites

No special prerequisites needed. This is a static website that can be opened directly in a web browser.

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser

### Local Development

For a better development experience, you can use a local server:

**Using Python:**

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (with http-server):**

```bash
npx http-server
```

**Using PHP:**

```bash
php -S localhost:8000
```

Then navigate to `http://localhost:8000` in your browser.

## Features Breakdown

### Navigation

- Sticky navbar that stays at the top while scrolling
- Smooth scroll to sections
- Active link highlighting based on scroll position
- Mobile-responsive hamburger menu

### Hero Section

- Prominent headline and company value proposition
- Quote request form with fields for:
  - Name
  - Company Name
  - Mobile Number
  - Email
  - Service Type (Sales/Rental)
  - Color Preference
  - Volume Requirements

### Services Section

- Four service cards with images and descriptions:
  1. Copier Rental
  2. Copier Sales
  3. Consumables & Parts
  4. Maintenance & Service

### Problem-Solution Section

- Highlights common pain points businesses face
- Positions Golden Cup as the solution provider

### About Us Section

- Company history and mission
- Interactive image carousel with navigation arrows and dots

### Footer

- Company logo and description
- Contact information (address, phone, email)
- Business hours
- Social media links

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contact Information

**Golden Cup Exim Marketing Corporation**

- **Address**: 2437 Tejeron Street, Sta. Ana, Manila, 1009, Philippines
- **Phone**: (02) 8562-0466 | (02) 8562-4566
- **Mobile**: (63) 917 870 7694 | (63) 919 994 7374
- **Email**: info@goldencupemc.com | billing@goldencupemc.com
- **Hours**: Mon-Fri 9:00AM - 5:00PM
- **Facebook**: [@Goldencupemc](https://www.facebook.com/Goldencupemc)

## License

© 2026 All Rights Reserved. Golden Cup Exim Marketing Corporation

## Notes

- The quote form in the hero section currently doesn't have backend functionality. You'll need to integrate it with a form handling service or backend API.
- All images are stored locally in the `assets/img/` directory.
- External dependencies (Bootstrap, Font Awesome) are loaded via CDN.
