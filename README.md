# 🌌 Galaxy Animation Project

A visually stunning web animation featuring a spinning galaxy with animated elements and bouncing corner decorations. Built with pure HTML and CSS.

![Project Preview](cool.jpeg)

## ✨ Features

- **Animated Galaxy Background** - Beautiful space imagery as the centerpiece
- **Spinning Center Element** - Smooth 360° rotation animation
- **Bouncing Corner Dragons** - Playful animated decorations in opposite corners
- **Dynamic Background** - Color-shifting effect for immersive experience
- **Fully Responsive** - Adapts to different screen sizes

## 🚀 Live Demo

[View Live Site](https://YOUR_USERNAME.github.io/galaxy-animation/)

## 🛠️ Technologies Used

- HTML5
- CSS3
- CSS Animations & Keyframes
- CSS Positioning & Transforms

## 📂 Project Structure
```
galaxy-animation/
├── index.html              # Main HTML file
├── styles.css              # All styling and animations
├── cool.jpeg              # Galaxy background image
├── p.gif                  # Spinning center element
├── haunted_3664027.png    # Black dragon (top-left)
├── haunted_3664056.png    # Blue dragon (bottom-right)
└── README.md              # Project documentation
```

## 🎨 Animations Included

1. **Background Color Change** - Smooth transition between purple and black (2s loop)
2. **Spinning Element** - 360° continuous rotation (3s loop)
3. **Bouncing Dragons** - Up and down bounce effect (1s loop, alternating)

## 💻 Installation & Setup

### Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/galaxy-animation.git
cd galaxy-animation
```

### Open Locally
Simply open `index.html` in your web browser:
```bash
# Windows
start index.html

# Mac
open index.html

# Linux
xdg-open index.html
```

## 🌐 Deploy Your Own

### GitHub Pages
1. Fork this repository
2. Go to Settings → Pages
3. Select `main` branch as source
4. Your site will be live at `https://YOUR_USERNAME.github.io/galaxy-animation/`

### Netlify
1. Drag and drop the project folder to [netlify.com](https://www.netlify.com)
2. Get instant deployment with auto-generated URL

## 🎓 What I Learned

- CSS keyframe animations
- Absolute and relative positioning
- Z-index layering for overlapping elements
- Transform properties (translate, rotate, scale)
- Creating responsive layouts
- Git version control and GitHub Pages deployment

## 🔮 Future Enhancements

- [ ] Add more interactive elements
- [ ] Include sound effects
- [ ] Create mobile-optimized version
- [ ] Add particle effects
- [ ] Implement parallax scrolling
- [ ] Add loading animation

## 📝 Code Highlights

### Spinning Animation
```css
@keyframes spin {
    0% {
        transform: translate(-50%, -50%) rotate(0deg);
    }
    100% {
        transform: translate(-50%, -50%) rotate(360deg);
    }
}
```

### Bounce Effect
```css
@keyframes bounce {
    0%, 100% {
        transform: translateY(0);
    }
    50% {
        transform: translateY(-30px);
    }
}
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).



⭐ **If you found this project interesting, please give it a star!** ⭐

---

Made with ❤️ and lots of CSS animations
