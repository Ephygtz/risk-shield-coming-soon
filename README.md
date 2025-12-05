# Risk Shield Legal - Coming Soon

A professional coming-soon landing page for Risk Shield Legal, featuring an email subscription form with countdown timer functionality.

## Overview

This project is a responsive, modern coming-soon website that showcases the Risk Shield Legal brand while building an email list of interested visitors. The page includes an animated countdown timer and email validation to collect subscriber information.

## Features

- **Responsive Design**: Mobile-first approach using Bootstrap grid system
- **Countdown Timer**: Real-time countdown to launch date powered by moment.js
- **Email Subscription Form**: Collects visitor emails with client-side validation
- **Custom Fonts**: Uses Barlow font family for consistent typography
- **Smooth Animations**: CSS animations for enhanced user experience
- **Icon Support**: Font Awesome 4.7.0 for beautiful icons
- **Form Validation**: Email format validation using regex patterns
- **Professional Styling**: Custom CSS with utility classes for flexible layouts

## Project Structure

```
riskshieldlegal.com/
├── index.html                 # Main landing page
├── README.md                  # This file
├── css/
│   ├── main.css              # Primary stylesheets
│   └── util.css              # Utility classes
├── js/
│   └── main.js               # Form validation and interactions
├── fonts/
│   ├── Barlow/               # Custom Barlow font files
│   └── font-awesome-4.7.0/   # Font Awesome icon library
├── images/
│   └── icons/                # Image assets and logos
└── vendor/
    ├── animate/              # CSS animation library
    ├── bootstrap/            # Bootstrap framework
    ├── countdowntime/        # Countdown timer library
    ├── jquery/               # jQuery library
    ├── select2/              # Select2 dropdown plugin
    └── tilt/                 # Tilt.js parallax effect
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styles and animations
- **JavaScript**: Form validation and interactivity
- **jQuery 3.2.1**: DOM manipulation
- **Bootstrap 4**: Responsive grid and components
- **Moment.js**: Date/time manipulation for countdown
- **Font Awesome 4.7.0**: Icon library
- **Select2**: Enhanced select dropdowns

## Getting Started

### Prerequisites

- A web server (Apache, Nginx, etc.)
- Modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. Clone or download the project to your web server's document root:
   ```
   /opt/lampp/htdocs/riskshieldlegal.com/
   ```

2. Ensure proper file permissions for the web server

3. Access the website through your browser:
   ```
   http://localhost/riskshieldlegal.com
   ```

## Configuration

### Countdown Timer

Edit the countdown timer settings in `index.html`:

```javascript
$('.cd100').countdown100({
    endtimeYear: 0,      // Target year
    endtimeMonth: 0,     // Target month
    // ... additional settings
});
```

Update the `endtimeYear` and `endtimeMonth` values to set your launch date.

## Form Validation

The email subscription form includes client-side validation:

- Email format validation using regex pattern
- Empty field validation
- Visual feedback with error highlighting
- Prevents form submission if validation fails

The form is located in the `.contact100-form` element and sends data to the server for processing.

## Customization

### Colors and Styling

Edit `css/main.css` to customize:
- Color scheme
- Typography
- Spacing and layout
- Animation effects

### Logo and Images

Replace image assets in the `images/` directory:
- Update `images/icons/RiskShiled-Logo.png` with your logo
- Update `images/bg01.jpg` with your background image

### Text Content

Edit text content directly in `index.html`:
- Main heading
- Tagline/description
- Call-to-action button text
- Footer text

## Browser Support

- Chrome/Edge (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome Android)

## Performance

The website is optimized for performance:
- Minified CSS and JavaScript files
- Optimized image assets
- CDN-delivered libraries (where applicable)
- Lightweight font subsetting

## License

© 2025 Risk Shield Legal. All rights reserved.

## Support

For questions or issues, please contact the development team or submit an issue through the project repository.

---

**Status**: Coming Soon Page | **Version**: 1.0.0
