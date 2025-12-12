# EnWithAI Website

A modern, single-page website for EnWithAI built with Last9.io-inspired design and theme.

## 🌱 About

This website showcases EnWithAI's intelligence-first engineering systems, featuring:
- **CrewPE**: AI-First Engineering Lifecycle Platform
- **EnginOS**: Operating System for Engineering Intelligence

## 🚀 Features

- **Modern Dark Theme**: Inspired by Last9.io's aesthetic with gradient accents
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile
- **Smooth Animations**: Fade-in effects, floating cards, and interactive elements
- **Single Page Navigation**: Smooth scrolling between sections
- **Performance Optimized**: Debounced scroll events and intersection observers

## 📁 Structure

```
├── index.html      # Main HTML file with all content sections
├── styles.css      # Complete styling with Last9.io-inspired theme
├── script.js       # Interactive features and animations
└── README.md       # This file
```

## 🎨 Design Elements

### Color Scheme
- **Background**: Dark (#0a0a0f, #131318)
- **Primary Accent**: Indigo (#6366f1)
- **Secondary Accent**: Purple (#8b5cf6), Cyan (#06b6d4)
- **Text**: White primary, gray secondary

### Key Sections
1. **Hero**: Engaging introduction with floating cards
2. **Problem Statement**: 6-card grid explaining engineering challenges
3. **Solution**: Architecture overview of EnginOS + CrewPE
4. **CrewPE Product**: 5 modules (Assist, Sense, Guide, Recall, Govern)
5. **EnginOS Platform**: Platform visualization and capabilities
6. **Target Audience**: ICPs and personas
7. **Team**: Founding team members
8. **Contact/CTA**: Call-to-action with features

## 🛠️ Technologies

- Pure HTML5
- CSS3 (Grid, Flexbox, Animations)
- Vanilla JavaScript (ES6+)
- Google Fonts (Inter)

## 💻 How to Use

### Option 1: Direct File Open
Simply open `index.html` in any modern web browser.

### Option 2: Local Server (Recommended)
```powershell
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using VS Code Live Server extension
Right-click index.html → "Open with Live Server"
```

Then visit: `http://localhost:8000`

## 🎯 Key Features Implemented

✅ Responsive navigation with mobile hamburger menu  
✅ Smooth scroll navigation  
✅ Intersection observer for scroll animations  
✅ Floating card animations in hero section  
✅ Gradient text highlights  
✅ Hover effects on cards and buttons  
✅ Active nav link highlighting on scroll  
✅ Performance-optimized with debouncing  
✅ Keyboard navigation support (ESC to close menu)  
✅ Console branding message  

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: Below 768px

## 🎨 Customization

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --color-accent-primary: #6366f1;
    --color-accent-secondary: #8b5cf6;
    /* ... more variables */
}
```

### Content
All content is in `index.html` with semantic HTML structure.

## 🚀 Performance

- Optimized scroll event listeners with debouncing
- Intersection Observer for lazy animations
- Minimal external dependencies
- Efficient CSS with reusable classes

## 📄 License

© 2025 EnWithAI. All rights reserved.

## 👥 Credits

**Design Inspiration**: Last9.io  
**Built for**: EnWithAI  
**Founding Team**: Parani Raja, Maathavan T, Koushik Ramani

---

**withai** = seed in Tamil 🌱
