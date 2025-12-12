# University College Website

A modern, responsive college website with beautiful animations and professional design.

## 🚀 Features

- **Responsive Design** - Works perfectly on all devices (desktop, tablet, mobile)
- **Modern Animations** - Smooth, professional animations throughout
- **Beautiful UI** - Attractive color scheme with gradient effects
- **Multiple Sections**:
  - Hero Section with animated particles
  - About Us with statistics
  - Courses showcase
  - Facilities overview
  - Gallery
  - Testimonials
  - News & Events
  - Contact Form with EmailJS integration

## 📁 Project Structure

```
collage project/
│
├── index.html          # Main HTML file
├── styles.css          # All styling and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

1. **Clone or Download** this project
2. **Open** `index.html` in your web browser
3. **No build process required** - it's a static website!

## 📧 EmailJS Configuration

To enable the contact form email functionality:

1. Sign up for a free account at [EmailJS](https://www.emailjs.com/)
2. Create an email service (Gmail, Outlook, etc.)
3. Create an email template
4. Get your:
   - Public Key
   - Service ID
   - Template ID
5. Update `script.js` with your credentials:
   ```javascript
   emailjs.init("YOUR_PUBLIC_KEY");
   emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', templateParams)
   ```

## 🎨 Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #a855f7;
    --gradient-start: #6366f1;
    --gradient-mid: #8b5cf6;
    --gradient-end: #ec4899;
}
```

### Content
- Update college name, contact info in `index.html`
- Modify course details, statistics, testimonials
- Add your own images to the gallery section

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🎯 Features Breakdown

### Navigation
- Fixed navigation bar with smooth scrolling
- Mobile-responsive hamburger menu
- Active link highlighting on scroll

### Hero Section
- Animated gradient background
- Floating particles effect
- Solo animated logo element
- Call-to-action buttons

### Animations
- Scroll-triggered animations
- Hover effects on cards
- Smooth transitions
- Loading animation
- Parallax effects

### Forms
- Contact form with validation
- Newsletter subscription
- EmailJS integration ready

## 🔧 Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling and animations
- **JavaScript** - Interactivity
- **Font Awesome** - Icons
- **EmailJS** - Email service (optional)

## 📝 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Feel free to fork this project and customize it for your needs!

## 📞 Support

For questions or issues, please open an issue or contact the development team.

## 🎓 Credits

- Icons: Font Awesome
- Email Service: EmailJS
- Design: Custom design with modern UI/UX principles

---

**Made with ❤️ for educational purposes**






