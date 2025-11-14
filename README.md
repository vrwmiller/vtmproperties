# vtm properties Website

A modern, responsive real estate website built for Cloudflare Pages.

## Features

- **Responsive Design**: Built with Bootstrap 5 for mobile-first responsive design
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Fast Performance**: Optimized for Cloudflare Pages with minimal dependencies
- **SEO Friendly**: Semantic HTML structure with proper meta tags
- **Accessibility**: WCAG compliant with proper ARIA labels and keyboard navigation

## Pages

- **Home**: Hero section with company overview
- **About**: Detailed information about vtm properties and services
- **For Rent**: Current rental property listings
- **For Sale**: Properties available for purchase
- **Contact**: Contact forms and mailing list signup

## Technologies Used

- HTML5
- CSS3 (Custom styles + Bootstrap 5)
- Vanilla JavaScript
- Bootstrap Icons
- Google Forms integration

## Deployment

This site is designed for Cloudflare Pages:

1. Push to GitHub repository
2. Connect repository to Cloudflare Pages
3. Deploy with these settings:
   - Build command: (none needed)
   - Build output directory: `/`
   - Root directory: `/`

## Local Development

Simply open `index.html` in a web browser or serve with any static file server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

## Project Structure

```text
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Custom styles
├── js/
│   └── script.js      # Interactive functionality
├── README.md          # This file
└── .gitignore         # Git ignore rules
```

## Contact

For questions about vtm properties, use the contact forms on the website.

## License

Copyright 2024 by vtm properties - All Rights Reserved
