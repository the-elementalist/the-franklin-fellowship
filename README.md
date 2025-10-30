# Fellowship Website

A modern, responsive website inspired by the Sophie Fellowship website. Built with HTML, CSS, and JavaScript.

## 🎨 Design Features

- **Modern UI/UX**: Clean and professional design with smooth animations
- **Responsive**: Fully responsive design that works on all devices (mobile, tablet, desktop)
- **Accessibility**: Includes skip links, ARIA labels, and keyboard navigation support
- **Smooth Animations**: Fade-in effects, parallax scrolling, and interactive elements
- **Color Scheme**: Purple/maroon color palette (#472836) inspired by the original site

## 📁 Project Structure

```
fellowship-website/
├── index.html       # Homepage
├── overview.html    # Program overview
├── schedule.html    # Fellowship schedule
├── fellows.html     # Fellows information
├── team.html        # Team members
├── apply.html       # Application page
├── faqs.html        # Frequently asked questions
├── styles.css       # All styling and responsive design
├── script.js        # Interactive functionality
├── assets/          # Images and media files
│   └── logo.png     # Site logo
└── README.md        # This file
```

## ✨ Key Sections

1. **Navigation Bar**: Sticky navigation with smooth scrolling
2. **Hero Section**: Eye-catching gradient background with title
3. **Notice Section**: Important announcements and contact information
4. **Mission Section**: Program mission and goals (dark background)
5. **Info Cards**: Team, Cost, and Application information in card layout
6. **Partnership Section**: Partner organization logos
7. **Questions Section**: FAQ and contact information
8. **Social Media**: Social media links
9. **Newsletter**: Email subscription form
10. **Footer**: Copyright and contact information

## 🚀 How to Use

### Option 1: Open Directly
Simply double-click on `index.html` to open it in your default browser.

### Option 2: Use a Local Server
For the best experience, use a local server:

```bash
# If you have Python 3 installed:
python3 -m http.server 8000

# If you have Python 2 installed:
python -m SimpleHTTPServer 8000

# If you have Node.js installed:
npx http-server -p 8000
```

Then open your browser and go to: `http://localhost:8000`

## 🎨 Customization

### Colors
Edit the CSS variables in `styles.css` (lines 8-15):

```css
:root {
    --primary-color: #472836;      /* Main purple/maroon */
    --secondary-color: #6B4A5A;    /* Secondary purple */
    --accent-color: #8B6478;       /* Accent color */
    --dark-bg: #2D1B24;            /* Dark background */
    --light-bg: #F9F9F9;           /* Light background */
    /* ... more colors ... */
}
```

### Fonts
The site uses:
- **Comfortaa** for headings (matching Sophie Fellowship)
- **Inter** for body text

These are loaded from Google Fonts and can be changed in the `<head>` of `index.html`.

### Content
Edit the text directly in `index.html` to customize:
- Program name
- Mission statement
- Team information
- Email addresses
- Social media links

## 🌟 Features

- ✅ Fully responsive design
- ✅ Smooth scroll navigation
- ✅ Mobile hamburger menu
- ✅ Animated info cards
- ✅ Parallax hero section
- ✅ Newsletter subscription form
- ✅ Accessibility features
- ✅ Cross-browser compatible
- ✅ No dependencies required

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔗 Inspired By

This website is inspired by [The Sophie Fellowship](https://www.sophiefellowship.in/) - a training program and fellowship for students preparing for IMO, EGMO, INMO and other mathematical competitions.

## 📝 License

Free to use and modify for your own projects.

## 🛠️ Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, CSS Variables, Animations)
- Vanilla JavaScript (ES6+)
- Google Fonts (Comfortaa, Inter)

---

Built with ❤️ and inspiration from Sophie Fellowship

