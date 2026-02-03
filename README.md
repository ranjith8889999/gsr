# Standing Corporator Website

A modern, professional website showcasing the work and community service of a standing corporator, featuring signature events like Kotideepotsavam and Reddys Community Vanabhojanalu.

![Website Preview](https://img.shields.io/badge/Status-Ready%20to%20Deploy-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🌟 Features

### Core Functionality
- **Responsive Design** - Seamlessly adapts to mobile, tablet, and desktop screens
- **Smooth Navigation** - Animated scroll transitions between sections
- **Interactive Gallery** - Filterable photo gallery with category tabs
- **Video Integration** - Embedded video players for event highlights
- **Contact Form** - Functional contact form for community engagement
- **Mobile Menu** - Hamburger menu for mobile devices

### Design Elements
- **Modern Gradients** - Beautiful color transitions and effects
- **Smooth Animations** - Fade-in, slide-up, and hover effects
- **Professional Typography** - Using Poppins font family
- **Icon Integration** - Font Awesome icons throughout
- **Counter Animations** - Animated statistics on scroll
- **Timeline Layout** - Interactive journey timeline

## 📁 Project Structure

```
gsr/
│
├── index.html              # Main HTML file
├── styles.css              # Complete styling and animations
├── script.js               # Interactive features and functionality
├── README.md               # This file
│
└── imagesvideos/           # Media assets folder
    ├── README.md           # Guide for adding images/videos
    ├── hero-bg.jpg         # Hero section background
    ├── corporator-photo.jpg # Profile photo
    ├── kotideepotsavam-main.jpg
    ├── koti-1.jpg
    ├── koti-2.jpg
    ├── koti-3.jpg
    ├── koti-video-thumb.jpg
    ├── vanabhojanalu-main.jpg
    ├── vana-1.jpg
    ├── vana-2.jpg
    ├── vana-3.jpg
    ├── vana-video-thumb.jpg
    ├── kotideepotsavam-2024.mp4
    └── vanabhojanalu-2024.mp4
```

## 🎯 Website Sections

### 1. Navigation Bar
- Fixed top navigation with smooth scroll
- Responsive hamburger menu for mobile
- Quick links to all sections

### 2. Hero Section
- Full-screen landing page
- Call-to-action buttons
- Animated scroll indicator

### 3. About Section
- Corporator profile and biography
- Animated statistics counter
  - 5000+ Families Helped
  - 10+ Major Events
  - 100% Dedication

### 4. Journey Timeline
- Interactive timeline showing milestones:
  - **2023**: Beginning of service
  - **2024**: First Kotideepotsavam & Vanabhojanalu
  - **2025**: Continued community service

### 5. Events Section
- **Kotideepotsavam** (2024 & 2025)
  - Festival of lights with 5000+ participants
  - Thousands of diyas lit with devotion
  - Community prayers and cultural programs
  
- **Reddys Community Vanabhojanalu** (2024 & 2025)
  - Traditional community feast
  - 1000+ Reddy community members
  - Cultural performances and elder blessings

### 6. Gallery Section
- Filterable photo gallery (All, Kotideepotsavam, Vanabhojanalu)
- Hover effects with image zoom
- Video section with embedded players

### 7. Contact Section
- Contact information display
- Interactive contact form
- Social media links
- Office hours and address

### 8. Footer
- Quick links
- About information
- Social media connections
- Copyright notice

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.) for editing
- Your event photos and videos

### Installation

1. **Clone or Download** this project to your computer

2. **Add Your Media Files**
   - Place all images and videos in the `imagesvideos/` folder
   - Follow the naming convention in `imagesvideos/README.md`
   - Recommended image formats: JPG, PNG
   - Recommended video format: MP4

3. **Customize Content**
   - Open `index.html` in a text editor
   - Update contact information (phone, email, address)
   - Modify text content to match your needs
   - Adjust social media links

4. **Run the Website**
   
   **Windows (PowerShell):**
   ```powershell
   Start-Process index.html
   ```
   
   **Alternative Methods:**
   - Double-click `index.html` or
   - Right-click and select "Open with" → Your browser
   - Or use a local server for testing

## 📸 Image Requirements

| Image Name | Purpose | Recommended Size |
|------------|---------|------------------|
| hero-bg.jpg | Hero background | 1920x1080px |
| corporator-photo.jpg | Profile photo | 800x1000px |
| kotideepotsavam-main.jpg | Event card | 1200x800px |
| koti-1.jpg, koti-2.jpg, koti-3.jpg | Gallery images | 800x600px |
| vanabhojanalu-main.jpg | Event card | 1200x800px |
| vana-1.jpg, vana-2.jpg, vana-3.jpg | Gallery images | 800x600px |
| Video thumbnails | Video posters | 640x360px |

### Video Files
- `kotideepotsavam-2024.mp4` - Event highlights video
- `vanabhojanalu-2024.mp4` - Event moments video

**Note:** Optimize images for web (compress to under 500KB when possible) for faster loading.

## 🎨 Customization Guide

### Changing Colors
Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #ff6b35;     /* Main accent color */
    --secondary-color: #004e89;   /* Headings and text */
    --accent-color: #ffa41b;      /* Highlights */
}
```

### Updating Contact Information
Edit these sections in `index.html`:
- Line ~350: Office address
- Line ~360: Phone number
- Line ~370: Email address
- Line ~380: Office hours
- Line ~390: Social media links

### Adding More Gallery Items
In the gallery section, duplicate this structure:

```html
<div class="gallery-item" data-category="your-category">
    <img src="imagesvideos/your-image.jpg" alt="Description">
    <div class="gallery-overlay">
        <h4>Title</h4>
        <p>Description</p>
    </div>
</div>
```

## 🌐 Deployment Options

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files
3. Enable GitHub Pages in repository settings
4. Access via `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)
1. Create a Netlify account
2. Drag and drop your project folder
3. Get instant hosting with custom domain support

### Option 3: Traditional Web Hosting
1. Purchase hosting and domain
2. Upload files via FTP/cPanel
3. Access via your custom domain

## 📱 Browser Compatibility

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with flexbox & grid
- **JavaScript (Vanilla)** - Interactive functionality
- **Font Awesome 6.4** - Icon library
- **Google Fonts** - Poppins typography

## ⚡ Performance Features

- Optimized animations for smooth 60fps
- Lazy loading for images
- Efficient JavaScript event handling
- Minimal external dependencies
- Mobile-first responsive design

## 📝 Maintenance Tips

### Regular Updates
- Keep event information current
- Add new photos after each event
- Update statistics and achievements
- Refresh contact information as needed

### Testing Checklist
- [ ] All images load correctly
- [ ] Videos play in different browsers
- [ ] Contact form validates input
- [ ] Mobile menu works properly
- [ ] All links are functional
- [ ] Gallery filtering works
- [ ] Smooth scrolling functions

## 🤝 Contributing

Want to enhance this website? Here are some ideas:
- Add a blog section for regular updates
- Integrate with social media APIs
- Add language translation options
- Create an admin panel for content management
- Add photo upload functionality

## 📞 Support

For questions or customization help:
- Review the code comments in HTML, CSS, and JS files
- Check `imagesvideos/README.md` for media guidelines
- Modify content carefully to maintain functionality

## 📄 License

This project is open source and available for personal and commercial use.

## 🎉 Acknowledgments

- Design inspired by modern political and community leader websites
- Built with dedication for community service showcase
- Optimized for Indian regional context and cultural events

---

**Version:** 1.0.0  
**Last Updated:** December 14, 2025  
**Status:** Production Ready ✅

---

### Quick Start Command

To open the website immediately:

**Windows (PowerShell):**
```powershell
Start-Process index.html
```

**Windows (Command Prompt):**
```cmd
start index.html
```

**macOS:**
```bash
open index.html
```

**Linux:**
```bash
xdg-open index.html
```

**Made with ❤️ for community service and development**