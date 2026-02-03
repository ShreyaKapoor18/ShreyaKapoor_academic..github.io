# Shreya Kapoor - Personal Portfolio Website

Professional academic portfolio website for computational neuroscience and AI research.

## 🌐 Live Site
[https://ShreyaKapoor18.github.io](https://ShreyaKapoor18.github.io)

## 📋 Features

- **Modern, Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Professional Aesthetic**: Clean design with academic focus
- **Interactive Elements**: Smooth scrolling, hover effects, and animations
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Fast Loading**: Minimal dependencies, optimized CSS and JavaScript

## 🚀 Quick Start

### Option 1: Deploy to GitHub Pages (Recommended)

1. **Fork or clone this repository**
   ```bash
   git clone https://github.com/ShreyaKapoor18/ShreyaKapoor18.github.io.git
   cd ShreyaKapoor18.github.io
   ```

2. **Add your profile image**
   - Place your profile photo in the `images/` folder as `profile.png`
   - Recommended size: 400x400 pixels (will be displayed as 200x200)

3. **Customize content** (Optional)
   - Edit `index.html` to update any personal information
   - Modify `css/style.css` to change colors or styles
   - Update `js/main.js` for custom interactions

4. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial setup of portfolio website"
   git push origin main
   ```

5. **Enable GitHub Pages**
   - Go to your repository Settings
   - Navigate to "Pages" section
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be live at `https://ShreyaKapoor18.github.io`

### Option 2: Local Development

1. **Open the site locally**
   - Simply open `index.html` in your web browser
   - Or use a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js
   npx http-server
   ```

2. **View in browser**
   - Navigate to `http://localhost:8000`

## 📁 File Structure

```
ShreyaKapoor18.github.io/
├── index.html              # Main homepage
├── css/
│   └── style.css          # All styling
├── js/
│   └── main.js            # Interactive features
├── images/
│   └── profile.png        # Your profile photo (add this)
├── cv/
│   └── cv.html            # CV page (optional)
├── publications/
│   └── index.html         # Publications page (optional)
└── README.md              # This file
```

## 🎨 Customization Guide

### Colors
Edit the CSS variables in `css/style.css`:
```css
:root {
    --primary: #1a3a52;        /* Main dark blue */
    --accent: #d4af37;         /* Gold accent */
    --text: #2c2c2c;           /* Text color */
    --light-bg: #f8f9fa;       /* Light background */
}
```

### Fonts
Current fonts:
- **Headings**: Crimson Pro (serif)
- **Body**: DM Sans (sans-serif)

To change fonts, update the Google Fonts link in `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont&display=swap" rel="stylesheet">
```

### Content Sections
Each section in `index.html` is clearly labeled:
- About Me
- Research Experience
- Publications
- Technical Skills
- Recent Activities
- Awards
- Contact

Simply edit the HTML within each `<section>` tag.

## 📱 Mobile Responsive

The site is fully responsive with breakpoints at:
- Desktop: > 768px
- Tablet: 481px - 768px
- Mobile: < 480px

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with flexbox and grid
- **JavaScript**: Vanilla JS for interactions
- **Google Fonts**: Crimson Pro & DM Sans
- **No frameworks**: Pure HTML/CSS/JS for fast loading

## 📄 License

© 2025 Shreya Kapoor. All rights reserved.

Feel free to use this template for your own portfolio, but please:
1. Replace all content with your own information
2. Add attribution if you'd like (not required)
3. Don't claim the design as your own work

## 🤝 Contributing

This is a personal portfolio, but suggestions are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

## 📧 Contact

**Shreya Kapoor**
- Email: shreya.kapoor@fau.de
- LinkedIn: [linkedin.com/in/shreyakapoor18](https://www.linkedin.com/in/shreyakapoor18/)
- GitHub: [github.com/ShreyaKapoor18](https://github.com/ShreyaKapoor18)
- Google Scholar: [Profile](https://scholar.google.com/citations?user=4Y3fnjgAAAAJ&hl=en)

---

Built with ❤️ by Shreya Kapoor | Last updated: February 2026
