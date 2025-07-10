# Smart Home Control Interface

A simple and intuitive smart home control interface built with HTML, CSS, and JavaScript featuring responsive design and smooth hover effects.

## 🏠 Overview

Web interface for managing smart home devices with room overviews and toggle switches for device control.

## ✨ Features

- **Home Dashboard** - Overview of all rooms and devices
- **Device Control** - Toggle switches to turn devices on/off
- **Responsive Design** - Works on all screen sizes
- **Smooth Animations** - Hover effects and transitions
- **Easy Navigation** - Simple room-to-device navigation

## 🛠️ Technologies

- HTML5, CSS3, JavaScript
- Font Awesome icons
- Custom toggle switches

## 📁 Project Structure

```
smart-home-interface/
├── home.html          # Main homepage
├── devices.html       # Device control page
├── home.css          # Homepage styles
├── styles.css        # Common styles
├── switch.css        # Toggle switch styles
└── animation.css     # Hover effects
```

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/smart-home-interface.git
   ```

2. **Open in browser**:
   - Open `home.html` in your web browser
   - Or use Live Server in VS Code

## 📱 Rooms & Devices

### Rooms:
- Bedroom (12 devices)
- Living Room (11 devices) 
- Bathroom (10 devices)
- Kitchen (15 devices)
- Garden (13 devices)
- Study Room (18 devices)

### Sample Devices:
- Smart TV, Router, Air Conditioner
- Speaker, Headphones, Alarm System

## 🎨 Design

- **Colors**: Purple gradient theme (`rgb(185, 75, 236)`)
- **Effects**: Smooth hover transitions
- **Layout**: Card-based responsive design

## 🔧 Customization

Add new devices by copying this structure in `devices.html`:

```html
<div class="dev">
    <div class="tb">
        <i class="fa-solid fa-[icon]"></i>
        <h3>Device Name</h3>
        <p>Device Model</p>
    </div>
    <div class="sw">
        <label class="switch">
            <input type="checkbox">
            <span class="slider round"></span>
        </label>
    </div>
</div>
```

## 🔮 Future Features

- [ ] JavaScript state persistence
- [ ] Backend API integration
- [ ] Settings page
- [ ] Energy consumption charts
- [ ] Automation scheduling


⭐ Star this repository if you find it helpful!
