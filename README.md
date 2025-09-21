# Personal Website

A modern, responsive personal website built with HTML, CSS, and JavaScript.

## Features

- **Landing Page** (`index.html`) - Hero section with introduction and call-to-action
- **About Page** (`details.html`) - Detailed information about skills, experience, and background
- **Contact Page** (`mailbox.html`) - Contact form and contact information
- **CV Page** (`cv.html`) - Resume download and overview

## Pages Overview

### 1. Landing Page (index.html)
- Hero section with name and introduction
- Feature cards showcasing skills
- Call-to-action sections
- Responsive navigation

### 2. About Page (details.html)
- Personal story and background
- Skills section with progress bars
- Experience timeline
- Professional journey

### 3. Contact Page (mailbox.html)
- Contact form with validation
- Contact information display
- FAQ section
- Social media links

### 4. CV Page (cv.html)
- PDF download functionality
- CV preview and highlights
- Professional summary
- Key achievements

## Customization

### Personal Information
Update the following in each HTML file:
- Replace "Your Name" with your actual name
- Update email addresses and contact information
- Modify the personal story and experience details
- Add your actual skills and technologies

### Styling
- Colors can be changed in `styles.css`
- The main color scheme uses blue gradients (#2563eb, #667eea, #764ba2)
- Font is Inter from Google Fonts

### CV PDF
- Replace `cv.pdf` with your actual CV file
- The CV page will automatically link to your PDF

## File Structure

```
website/
├── index.html          # Landing page
├── details.html        # About page
├── mailbox.html        # Contact page
├── cv.html            # CV page
├── styles.css         # All styling
├── script.js          # JavaScript functionality
├── cv.pdf            # Your CV (replace with actual file)
└── README.md         # This file
```

## Features Included

- ✅ Responsive design (mobile-friendly)
- ✅ Modern UI with gradients and animations
- ✅ Contact form with validation
- ✅ Smooth scrolling and transitions
- ✅ Mobile navigation menu
- ✅ PDF download functionality
- ✅ Social media integration
- ✅ Accessibility features
- ✅ SEO-friendly structure

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Getting Started

1. Download all files to your web server
2. Replace placeholder content with your information
3. Add your actual CV PDF file
4. Update contact information
5. Customize colors and styling as needed
6. Deploy to your hosting service

## Contact Form

The contact form currently shows a success message but doesn't actually send emails. To make it functional:

1. Set up a backend service (Node.js, PHP, etc.)
2. Add form action and method attributes
3. Implement server-side email sending
4. Add CSRF protection

## License

This project is open source and available under the MIT License.
