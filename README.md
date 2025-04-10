# ✨ Design Playground

## 🌟 Overview

Design Playground is a modern, interactive showcase of 10 popular UI design styles and trends. From glassmorphism to brutalism, this collection demonstrates various design approaches with responsive layouts and subtle animations.

## 🔗 Live Demo

Visit the [Design Playground](https://vitthalr.github.io/ai/) to see it in action.

## 🚀 Features

- 🎆 **Stunning Visual Background**: Animated northern lights effect with dynamic hue rotation and floating bubble elements
- 🎨 **10 Unique Design Themes**:
  - 🔍 Glassmorphism
  - 🔘 Neumorphism
  - 📱 Skeuomorphism
  - 🏮 Claymorphism
  - 🌈 Aurora Gradient
  - 🌆 Vaporwave
  - 🏢 Brutalism
  - 🤖 Cyberpunk
  - ⚪ Minimalism
  - ❄️ Frosted UI
- 📱 **Responsive Design**: Optimized for mobile, tablet, and desktop viewing
- 🖱️ **Interactive Elements**: Hover effects, animations, and smooth transitions
- 👆 **Custom Cursor**: Enhanced user interaction with custom cursor effects
- ♿ **Accessibility Focused**: High contrast text and semantic HTML

## 🏁 Getting Started

### Prerequisites

- 🌐 A modern web browser (Chrome, Firefox, Safari, Edge)
- 💻 Basic understanding of HTML, CSS, and JavaScript for customization

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vitthalr/ai.git
   ```

2. Navigate to the project directory:
   ```bash
   cd ai
   ```

3. Open the `index.html` file in your browser or use a local development server:
   ```bash
   # Using Python's built-in server
   python -m http.server
   
   # Or with Node.js and npx
   npx serve
   ```

## 📂 Project Structure

```
design-playground/
├── index.html              # Main HTML file with project cards
├── styles.css              # Main stylesheet with all visual effects
├── README.md               # This documentation
└── [design-theme-name]/    # Individual project folders for each design theme
    ├── index.html          # HTML for the specific design
    └── styles.css          # CSS specific to the design theme
```

## ⚙️ Customization

### Changing Background Effects

The northern lights background and bubble animations can be customized in the `styles.css` file:

- Adjust animation speed by modifying the `animation-duration` values
- Change color schemes by updating the gradient colors in `.animated-bg`
- Modify bubble size and density by editing the `.bubbles span` properties

### Adding New Design Cards

To add a new design card, copy one of the existing card structures in `index.html` and update:

1. The link URL (`href` attribute)
2. Card class to match your design theme
3. Icon (using Font Awesome classes)
4. Content (title, description, etc.)

## 🛠️ Technologies Used

- HTML5
- CSS3 with advanced animations
- Vanilla JavaScript for interactions
- Font Awesome for icons
- Google Fonts (Inter & Outfit)

## 🌐 Browser Compatibility

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 80+

## 🤝 Contributing

Contributions are welcome! Feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👏 Acknowledgments

- Inspiration from various modern UI design trends
- Font Awesome for the icon set
- Google Fonts for typography

---

Created with ❤️ and CSS passion
