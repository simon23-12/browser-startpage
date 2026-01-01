# Browser Startpage

A beautiful, minimalist, and fully customizable browser starting page with animated network background and persistent link management.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red.svg)](https://github.com/yourusername/browser-startpage)

## Features

- **Dynamic Greeting**: Time-based greeting (Guten Morgen, Guten Tag, Guten Abend)
- **Animated Network Background**: Beautiful particle network with dynamic connections and glow effects
- **Customizable Quick Links**: Add, edit, and delete links with persistent localStorage
- **Light/Dark Mode**: Toggle between themes with automatic persistence
- **Glassmorphism Design**: Modern blur effects and translucent elements
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **Zero Dependencies**: Pure HTML, CSS, and JavaScript - no frameworks required

## Demo

🚀 **[Live Demo](https://yourusername.github.io/browser-startpage/)**

## Screenshots

### Dark Mode
![Dark Mode](assets/screenshot-dark.png)

### Light Mode
![Light Mode](assets/screenshot-light.png)

### Link Management
![Link Editor](assets/screenshot-modal.png)

## Installation

### Option 1: Set as Browser Homepage

1. Download or clone this repository
2. Open `index.html` in your browser
3. Set it as your homepage:
   - **Chrome**: Settings → Appearance → Show home button → Enter custom web address
   - **Firefox**: Settings → Home → Homepage and new windows → Custom URLs
   - **Edge**: Settings → Appearance → Customize toolbar → Show home button → Enter custom URL

### Option 2: Deploy to GitHub Pages

1. Fork this repository
2. Go to Settings → Pages
3. Select `main` branch as source
4. Your page will be available at `https://yourusername.github.io/browser-startpage/`

### Option 3: Use as New Tab Extension

1. Install a browser extension like "Custom New Tab URL"
2. Point it to your hosted version or local file

## Usage

### Managing Links

1. **View Links**: Hover over the greeting text to reveal the circular link menu
2. **Add Link**: Click the **+** button and fill in the label and URL
3. **Edit Link**: Hover over any link, click the **✏️** edit button
4. **Delete Link**: Hover over any link, click the **🗑️** delete button

All changes are automatically saved to your browser's localStorage.

### Toggle Theme

Click the toggle switch in the top-right corner to switch between light and dark mode. Your preference is saved automatically.

### Keyboard Shortcuts

- **ESC**: Close modal dialog
- **Enter**: Submit link form (when focused)

## Customization

### Change Your Name

Edit line 384 in `index.html`:

```javascript
greetingEl.textContent = 'Guten Morgen, Simon'; // Change "Simon" to your name
```

### Change Background Image

Replace the image source on line 506:

```html
<img src="your-image-url.png" alt="Network Background">
```

Or remove the image entirely for just the animated network effect.

### Adjust Colors

Modify CSS variables in the `<style>` section (lines 8-336) to customize colors, animations, and effects.

### Modify Animation

Adjust particle count, speed, and connection behavior in the JavaScript section (lines 617-838).

## Technical Details

### Built With

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations, glassmorphism, and grid layouts
- **Vanilla JavaScript** - No frameworks or libraries
- **Canvas API** - Particle network animation
- **LocalStorage API** - Persistent data storage

### Browser Support

- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Opera 76+

### Performance

- Lightweight: ~30KB total file size
- Zero external dependencies
- Optimized canvas animations (60 FPS)
- Adaptive particle count based on screen size

## File Structure

```
browser-startpage/
├── index.html          # Main application file
├── README.md           # This file
├── LICENSE             # MIT License
├── CONTRIBUTING.md     # Contribution guidelines
└── assets/             # Screenshots and demo assets
    ├── screenshot-dark.png
    ├── screenshot-light.png
    └── screenshot-modal.png
```

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

### Development Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/browser-startpage.git
   cd browser-startpage
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   python -m http.server 8000
   # or
   npx serve
   ```

3. Make your changes and test thoroughly

4. Submit a pull request

## Roadmap

- [ ] Export/Import settings
- [ ] Custom background upload
- [ ] Weather widget integration
- [ ] Time and date display
- [ ] Search bar integration
- [ ] Bookmark folders/categories
- [ ] Keyboard navigation
- [ ] Custom color themes
- [ ] PWA support with offline mode

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by modern minimalist design principles
- Network animation concept from generative art
- Glassmorphism trend from iOS and modern web design

## Author

**Simon**

- GitHub: [@yourusername](https://github.com/yourusername)

## Support

If you find this project useful, please consider:

- ⭐ Starring the repository
- 🐛 Reporting bugs via [Issues](https://github.com/yourusername/browser-startpage/issues)
- 💡 Suggesting new features
- 🔀 Contributing code via Pull Requests

---

**Made with ❤️ by Simon**
