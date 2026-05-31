# AL-Zakhrof Iron Factory | مصنع الزخرف للحديد

A modern, bilingual (Arabic/English) website for AL-Zakhrof Iron Factory, featuring interactive flipbook capabilities for showcasing company portfolios and documentation.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Configuration](#configuration)
- [License](#license)

---

## 🎯 Overview

AL-Zakhrof Iron Factory's website is designed to provide an engaging digital presence with interactive content. The site supports both Arabic (RTL) and English (LTR) layouts, featuring an innovative page-flip animation for showcasing catalogs and documentation.

---

## ✨ Features

- **Bilingual Support**: Full Arabic and English language support with RTL/LTR layout
- **Interactive Flipbook**: Dynamic page-turning animation for catalogs and brochures
- **Responsive Design**: Mobile-friendly layout that adapts to all screen sizes
- **Modern UI**: Clean and professional user interface with Arabic typography
- **Image Gallery**: Organized image sections (About, Documentation, Papers, Projects)
- **Font Awesome Icons**: Rich icon library for visual enhancement

---

## 📁 Project Structure

```
AL-Zakhrof/
├── index.html           # Main HTML file
├── package.json         # Project dependencies
├── README.md            # This file
├── css/
│   └── style.css        # Main stylesheet
├── js/
│   └── script.js        # Main JavaScript file
└── images/
    ├── about/           # About section images
    ├── doc/             # Documentation images
    ├── pap/             # Paper/publication images
    └── project/         # Project showcase images
```

---

## 📦 Requirements

- Node.js (for package management)
- Modern web browser with ES6+ support
- Internet connection (for external libraries)

---

## 🚀 Installation

1. **Clone or download the project**
   ```bash
   cd AL-Zakhrof
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Open in browser**
   - Simply open `index.html` in your web browser, or
   - Use a local server for better performance:
     ```bash
     npx http-server
     ```

---

## 💻 Usage

### Basic Setup
1. Open the project in your preferred code editor
2. Modify content in `index.html` as needed
3. Update styles in `css/style.css`
4. Add custom functionality in `js/script.js`

### Adding Images
Place images in the appropriate folders under `images/`:
- `/about/` - Company information images
- `/doc/` - Documentation and technical images
- `/pap/` - Papers and publications
- `/project/` - Project showcase images

### Configuring the Flipbook
The flipbook container can be customized through the inline styles in `index.html`:
- Adjust `width` and `height` for different screen sizes
- Modify `max-width` for responsive behavior
- Change `border-radius` for corner styling

---

## 🛠️ Technologies Used

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Semantic markup and structure |
| **CSS3** | Styling and responsive design |
| **JavaScript** | Interactivity and dynamic behavior |
| **Page Flip** | Interactive flipbook animation (v2.0.7+) |
| **Font Awesome** | Icon library |
| **Google Fonts** | Tajawal font for Arabic typography |

---

## ⚙️ Configuration

### External Libraries
The project uses the following external resources:

- **Page Flip Library**: `/dist/js/stPageFlip.css`
- **Font Awesome Icons**: CDN link `v6.4.0`
- **Google Fonts**: Tajawal font family (weights: 400, 500, 700, 900)

### Browser Compatibility
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

---

## 📝 Notes

- The site is configured with RTL (Right-to-Left) as the primary direction for Arabic support
- All text content should be responsive and support both languages
- The flipbook height is set to 600px minimum - adjust as needed
- Box shadows and styling are optimized for modern browsers

---

## 📞 Support

For issues or inquiries about the AL-Zakhrof Iron Factory website, please contact the development team.

---

## 📄 License

© 2024 AL-Zakhrof Iron Factory. All rights reserved.

---

**Last Updated**: June 2024
