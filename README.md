# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Features a dark green theme with elegant design and smooth animations.

## 🎨 Design Features

- **Dark Green Theme**: Custom color palette with #051F20 background and #8EB69B accents
- **Smooth Animations**: Reveal-on-scroll, hover effects, and custom cursor
- **Responsive Design**: Mobile-first approach with breakpoint at 900px
- **Modern Components**: Rounded cards, floating chips, and gradient effects

## 📁 File Structure

```
portfolio/
├── index.html          # Main homepage with all sections
├── projects.html       # All projects page with filtering
├── app-gallery.html    # Mobile app gallery with screenshots
└── README.md          # This file
```

## 🚀 Getting Started

1. **Open the website**: Simply open `index.html` in your web browser
2. **Local development**: Use a local server for best experience
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

## 📱 Sections Overview

### 1. **Hero Section**
- Animated profile card with floating chips
- Stats display (projects, years, passion)
- Call-to-action buttons

### 2. **About Section**
- Two-column layout with bio and profile image
- Social media links (Email, LinkedIn, GitHub, Twitter)
- Location badge overlay

### 3. **Education Section**
- Three education cards with progress bars
- Web Development (2024-2025)
- Mobile Development (2025-2026)
- Open Source & Projects (Ongoing)

### 4. **Skills Section**
- Simple bubble layout (no cards)
- 20 skills displayed as interactive bubbles
- Centered, responsive design

### 5. **Projects Section**
- Featured projects on homepage (3 web apps)
- "View All Projects" button links to projects.html

### 6. **Contact Section**
- Contact information cards
- Contact form with validation
- Location, email, phone, availability

## 🎯 Customization

### Colors
The color scheme is defined in CSS variables:
- `--c1: #051F20` (Background)
- `--c2: #0B2B26` (Card background)
- `--c3: #163832` (Secondary)
- `--c4: #235347` (Tertiary)
- `--c5: #8EB69B` (Primary accent)
- `--c6: #DAF1DE` (Text)

### Content
Update content directly in HTML files:
- **index.html**: Personal info, bio, education, skills, featured projects
- **projects.html**: All projects data in JavaScript array
- **app-gallery.html**: Mobile app gallery data (synced with projects.html)

### Adding Projects
In `projects.html`, add to the `projectsData` array:
```javascript
{
    id: 15,
    title: "Your Project",
    category: "web" or "mobile",
    description: "Project description",
    image: "path/to/image.png",
    icon: "fas fa-icon-name",
    tags: ["Tech1", "Tech2"],
    liveUrl: "https://...",
    githubUrl: "https://...",
    // For mobile apps only:
    apkUrl: "path/to/app.apk",
    gallery: ["screenshot1.png", "screenshot2.png"],
    galleryDescription: "Detailed description",
    galleryFeatures: ["Feature 1", "Feature 2"]
}
```

## 🔧 Features

### Interactive Elements
- **Custom Cursor**: Animated dot and ring cursor (desktop)
- **Smooth Scrolling**: Navigation links scroll smoothly to sections
- **Form Validation**: Contact form with email validation
- **Reveal Animations**: Elements fade up when scrolled into view
- **Hover Effects**: Cards and buttons with transform effects
- **Ripple Effects**: Button click animations
- **Lightbox Gallery**: Click screenshots to view full-size with keyboard navigation

### Project Features
- **Filtering**: Filter projects by All/Mobile/Web on projects.html
- **Dynamic Buttons**: 
  - Web apps: "Live" + "Code" buttons
  - Mobile apps: "App Photos" + "Code" + "Install APK" buttons
- **App Gallery**: Dedicated page for mobile app screenshots and details

### Responsive Design
- **Mobile Breakpoint**: 900px (navbar), 600px (layout)
- **Hamburger Menu**: Mobile navigation menu
- **Flexible Grids**: Auto-fit columns for projects and skills
- **Stacked Layouts**: Single column on mobile devices

## 🛠️ Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📝 Usage

1. **Personalize Content**: Update HTML with your information
2. **Add Profile Images**: Replace image paths in hero and about sections
3. **Update Projects**: Add your projects to the data array in projects.html
4. **Add Screenshots**: For mobile apps, add screenshot paths to `gallery` array
5. **Add APK Files**: Upload APK files and link them in `apkUrl`
6. **Deploy**: Upload to your web hosting service

## 🚀 Pages

### index.html
- Homepage with all main sections
- Features 3 web projects
- Links to projects.html for full portfolio

### projects.html
- Complete project portfolio (9 web + 5 mobile apps)
- Filter by category (All/Mobile/Web)
- Dynamic rendering from JavaScript data
- Mobile apps link to app-gallery.html

### app-gallery.html
- Dedicated mobile app showcase page
- Displays app details, features, and screenshots
- Lightbox for full-screen image viewing
- Reads project ID from URL parameter (?id=10)

## 📞 Contact

- **Email**: sifedinebammarouf@gmail.com
- **LinkedIn**: [Sifedin Bammarouf](https://linkedin.com/in/sifedin-bammarouf-3b8750370)
- **GitHub**: [sifedine01](https://github.com/sifedine01)

---

**Built with ❤️ in Morocco 🇲🇦 using HTML, CSS, and JavaScript** 