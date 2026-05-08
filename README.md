# Nitrro Zone 360 - Gym Website

A modern, responsive website for **Nitrro Zone 360**, a premier fitness center located in Balewadi, Pune. This project showcases gym facilities, membership plans, and provides an engaging platform for potential members to learn about the gym and get in touch.

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34C26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## 📋 Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Page Overview](#page-overview)
- [Key Features](#key-features)
- [Contributors](#contributors)
- [License](#license)

---

## ✨ Features

### 🎬 **Video Background Landing Page**
- Full-screen auto-playing video background with overlay
- Smooth fade-in animations for engaging user experience
- Call-to-action button to explore memberships

### 💪 **Membership Plans**
Four tiered membership options:
- **1 Month** - ₹5,000
- **3 Months** - ₹12,000
- **6 Months** - ₹15,000 (with diet consultation)
- **1 Year** - ₹20,000 (includes massage chair session)

### 🌅 **Image Gallery**
Showcase of gym facilities, equipment, and member testimonials

### 📞 **Contact Page**
- Complete contact information (address, phone, email)
- Google Maps integration for location
- Operating hours display

### 🔐 **Login Page**
- User authentication interface
- Responsive design

### 🌓 **Dark Mode**
- Toggle between light and dark themes
- Persisted user preference using localStorage
- Smooth transitions between modes

### 📱 **Fully Responsive Design**
- Mobile-first approach
- Optimized for desktop, tablet, and mobile devices
- Smooth animations and transitions

### ⚡ **Performance Optimized**
- Efficient CSS and JavaScript
- Optimized video playback
- Fast loading times

---

## 📁 Project Structure

```
Simple-Gym-Website-main/
│
├── index.html                 # Home page
│
├── html/
│   ├── contact.html          # Contact page
│   ├── imageg.html           # Image gallery
│   ├── login.html            # Login page
│   └── membership.html       # Membership details
│
├── css/
│   ├── index.css             # Home page styles
│   ├── contact.css           # Contact page styles
│   ├── imageg.css            # Gallery styles
│   ├── login.css             # Login page styles
│   └── membership.css        # Membership page styles
│
├── js/
│   └── darkmode.js           # Dark mode toggle functionality
│
├── img/                       # Images and logos
│   └── The-Zone-Logo-with-uper-text.png
│
├── vid/                       # Video files
│   └── fullvideoshoot.mp4    # Background video
│
├── gallery/                   # Gallery content
│
└── README.md                  # Project documentation
```

---

## 🛠 Technologies Used

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Semantic markup and structure |
| **CSS3** | Styling, animations, and responsive design |
| **Vanilla JavaScript** | Dark mode functionality, interactivity |
| **LocalStorage API** | Persistent dark mode preference |
| **Google Maps API** | Location embedding |
| **MP4 Video** | Background media |

---

## 🚀 Setup & Installation

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server-side dependencies required
- Works offline (except Google Maps feature)

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/Simple-Gym-Website-main.git
   cd Simple-Gym-Website-main
   ```

2. **Open in Browser**
   - Double-click `index.html` to open locally, OR
   - Use a local server for better performance:
   
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (if installed)
   npx http-server
   ```

3. **Navigate to Website**
   - Open `http://localhost:8000` in your browser (if using server)
   - Or simply open `index.html` directly

---

## 💻 Usage

### Navigation
- **Home** - Main landing page with featured content
- **Image Gallery** - Browse gym facilities and member photos
- **Membership Plans** - View pricing and plan details
- **Contact Us** - Get in touch with the gym
- **Login** - Member login portal

### Dark Mode
- Click the **🌙** (moon) icon in the top-right corner
- Toggle to **☀️** (sun) icon in dark mode
- Your preference is automatically saved

### Responsive Behavior
- Website automatically adapts to different screen sizes
- Optimized for:
  - Mobile (320px and up)
  - Tablet (768px and up)
  - Desktop (1024px and up)

---

## 📄 Page Overview

### 🏠 **Home Page** (`index.html`)
- Video background with overlay
- Membership plans overview
- Facilities showcase
- Animated call-to-action buttons

### 🖼 **Image Gallery** (`html/imageg.html`)
- Visual showcase of gym equipment
- Member transformation stories
- Facility photographs

### 💳 **Membership Plans** (`html/membership.html`)
- Detailed plan comparison
- Benefits breakdown
- Easy signup process

### 📧 **Contact Page** (`html/contact.html`)
- Gym address and location map
- Phone and email contact
- Operating hours
- Google Maps integration

### 🔑 **Login Page** (`html/login.html`)
- User authentication interface
- Password recovery option

---

## 🎯 Key Features Explained

### Dark Mode Implementation
The dark mode is implemented using:
- CSS custom properties (variables)
- JavaScript event listeners
- LocalStorage for persistence
- Smooth transition effects

```javascript
// Toggle dark mode and save preference
toggleBtn.addEventListener("click", () => {
  body.classList.toggle("dark-mode");
  localStorage.setItem("darkMode", body.classList.contains("dark-mode") ? "enabled" : "disabled");
});
```

### Animations
- Fade-in effects on page load
- Delay sequences for staggered animations
- Smooth transitions on theme changes
- Hover effects on buttons and links

### Video Background
- Auto-playing video for dynamic landing page
- Brightness filter overlay for text readability
- Responsive sizing (covers full viewport)
- Fallback for unsupported browsers

---

## 🤝 Contributors

- **Nishad Patil** - Developer
- **SY CSE 2** - Academic Year 2025-26

---

## 📝 License

This project is licensed under the **MIT License** - feel free to use, modify, and distribute.

---

## 🔗 Links

- **Location**: [Nitrro Zone 360, Balewadi, Pune](https://maps.app.goo.gl/prGZMPPDPqiURssb8)
- **Contact**: zone360balewadi@gmail.com
- **Phone**: +91 941818 4040

---

## 📱 Contact & Support

For inquiries about memberships or gym facilities:
- **Email**: zone360balewadi@gmail.com
- **Phone**: +91 941818 4040
- **Hours**: Mon–Sat: 6 AM – 10 PM | Sun: 8 AM – 1 PM

---

## 🎨 Customization

### Colors
Edit CSS variables in the `:root` selector to change theme colors:
```css
:root {
  --bg-gradient: linear-gradient(to right, #0037ff, #ff6f00);
  --text-color: #f0f0f0;
}
```

### Membership Plans
Update prices and benefits in `index.html` membership section

### Contact Information
Modify details in `html/contact.html` and update map embed URL

### Video Background
Replace `vid/fullvideoshoot.mp4` with your own video file

---

## ✅ Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Edge | ✅ Full |
| IE 11 | ❌ Not Supported |

---

**Made with 💪 for Nitrro Zone 360**
