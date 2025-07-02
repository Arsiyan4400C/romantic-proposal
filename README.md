# 💖 Romantic Proposal Website

A beautiful, interactive proposal website with stunning animations and effects to make your special moment unforgettable.

## ✨ Features

- **Animated Background**: Dynamic gradient shifts and floating particles
- **Interactive Hearts**: Continuous heart animations floating across the screen
- **Glass Morphism Design**: Modern frosted glass card design
- **Playful "No" Button**: The "No" button moves around and gets smaller with each click
- **Celebration Effects**: Fireworks and enhanced animations when "Yes" is clicked
- **Responsive Design**: Works perfectly on mobile and desktop devices
- **Smooth Animations**: CSS3 and JavaScript powered smooth transitions
- **Easter Egg**: Hidden Konami code for extra fireworks!

## 🚀 Live Demo

Visit the live demo: [Your GitHub Pages URL]

## 📱 Screenshots

*Add screenshots of your website here*

## 🛠️ Setup & Deployment

### Quick Deploy to GitHub Pages

1. **Fork this repository** or create a new repository
2. **Upload the files**:
   - `index.html` (main website file)
   - `README.md` (this file)
3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"
4. **Your site will be live** at: `https://Arsiyan4400C/romantic-proposal`

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/Arsiyan4400C/romantic-proposal.git
   ```

2. Open `index.html` in your browser or use Live Server in VS Code

## 🎨 Customization

### Changing Colors
Edit the CSS variables in the `<style>` section:
- Background gradient: Update the `background` property in `body`
- Button colors: Modify `.yes` and `.no` classes
- Heart colors: Change colors in the heart CSS

### Adding Your Own Messages
Update the `noMessages` array in the JavaScript section:
```javascript
const noMessages = [
  "Your custom message 1",
  "Your custom message 2",
  // Add more messages
];
```

### Modifying Animations
- **Particle count**: Change the loop in `createParticles()` function
- **Heart frequency**: Adjust the interval in `createHearts()` function  
- **Animation speeds**: Modify CSS animation durations

## 📋 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Performance

- **Lightweight**: No external dependencies except Google Fonts
- **Optimized animations**: GPU-accelerated CSS transforms
- **Memory efficient**: Automatic cleanup of animation elements
- **Mobile optimized**: Touch-friendly responsive design

## 🛡️ Privacy & Security

- **No data collection**: Everything runs locally in the browser
- **No external requests**: Except for Google Fonts (can be made offline)
- **No cookies**: Pure client-side application

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 💡 Ideas for Enhancement

- [ ] Add music/sound effects
- [ ] Photo gallery integration
- [ ] Multiple language support
- [ ] Save responses to local storage
- [ ] Add countdown timer
- [ ] Social media sharing buttons
- [ ] Custom photo backgrounds
- [ ] Voice message integration

## 💌 Credits

Created with 💖 for making marriage proposals magical and memorable.

**Fonts**: Google Fonts (Great Vibes, Poppins)
**Icons**: Emoji and CSS-created hearts
**Inspiration**: Love and the desire to create magical moments

---

*Made with ❤️ for love stories around the world*
