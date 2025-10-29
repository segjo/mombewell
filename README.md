# MomBeWell Website

A single-page responsive website built with Bootstrap 5 framework.

## Features

✨ Modern, clean design with Bootstrap 5
📱 Fully responsive (mobile, tablet, desktop)
📄 Lightweight (< 10MB)
📧 Contact form with email integration

## Sections

1. **Hero Section** - Title with round logo image
2. **Welcome Text** - Introduction to MomBeWell
3. **Our Offers** - Service cards with PDF download links
4. **Contact Form** - Request current courses information
5. **Location & Team** - Address information and team photo
6. **Footer** - Contact email and social media links

## File Structure

```
mombewell/
├── index.html          # Main website file
├── styles.css          # Custom styles
├── images/
│   ├── home.webp      # Home page image
│   └── team.webp      # Team photo image
├── pdfs/
│   ├── .htaccess      # Apache configuration for PDF downloads
│   ├── MomBeWell-Kurs.pdf  # Course information PDF
│   └── README.md      # PDF directory documentation
└── README.md          # This file
```

## Technologies Used

- **Bootstrap 5.3.2** - CSS framework (loaded via CDN)
- **Bootstrap Icons** - Icon library (loaded via CDN)
- **Vanilla JavaScript** - For form handling and smooth scrolling

## Content Management

### PDF Downloads
Course information and materials are stored in the `pdfs/` directory. The `.htaccess` file ensures proper content-type headers for PDF downloads.

### Images
All images are stored in WebP format for optimal performance:
- `home.webp` - Hero section background image
- `team.webp` - Team photo for the location section


### Add More Offers

To add more service cards, copy one of the existing offer card blocks and modify the content.

## Support

For questions or issues, contact: info@mombewell.ch

---

Made with ❤️ for MomBeWell
