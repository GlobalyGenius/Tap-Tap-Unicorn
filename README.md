# TAP-TAP UNICORN 🦄

<div align="center">

![TAP-TAP UNICORN](https://img.shields.io/badge/TAP--TAP-UNICORN-8A2BE2?style=for-the-badge&logo=unicorn&logoColor=white)
![Version](https://img.shields.io/badge/version-1.0.0-00CED1?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-success?style=for-the-badge)
![PWA](https://img.shields.io/badge/PWA-Enabled-5A0FC8?style=for-the-badge)

**The most addictive magical clicker game with unicorns, rainbows and enchantment!**

[Play Now](#-quick-start) • [Features](#-features) • [Demo](#-live-demo)

</div>

## 🌟 About The Project

**TAP-TAP UNICORN** is an incredibly addictive idle clicker game where you become a wizard capable of taming a magical unicorn! Tap the unicorn to earn Magic Points, buy upgrades, and unlock achievements in this colorful world of magic and rainbows.

### 🎯 Key Features

- ✨ **Magical Gameplay** - Tap the unicorn and watch magical effects
- 🚀 **Upgrade System** - 8 unique upgrades with progressive costs
- 🌈 **Rainbow Boost** - Temporary point multiplier for fast progress
- 🏆 **Achievement System** - 11 magical achievements to unlock
- ⭐ **Prestige System** - Reset the game with permanent bonuses
- 🌍 **Multi-language** - English, Russian, and Belarusian support
- 📱 **PWA Ready** - Install as a mobile app
- 🎨 **Beautiful UI** - Dark/Light themes with rainbow animations
- 💾 **Auto-save** - Your progress is always saved

## 🚀 Quick Start

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- For PWA: Mobile device or desktop browser that supports PWA

### Installation

1. **Clone the repository**
   bash
   git clone https://github.com/globalygenius/tap-tap-unicorn.git
   cd tap-tap-unicorn
   

2. **Serve the files**
   - Option 1: Use a local server
     bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve .
     
     # Using PHP
     php -S localhost:8000
     
   - Option 2: Open index.html directly in your browser

3. **Access the game**
   - Open your browser and navigate to http://localhost:8000
   - Or simply open index.html in your browser

### PWA Installation

1. Open the game in a supported browser (Chrome, Edge, Safari)
2. Click the install button in the address bar or
3. Use "Add to Home Screen" from the browser menu

## 🎮 How to Play

### Basic Gameplay

1. **Tap the Unicorn** 🦄
   - Click/tap the magical unicorn to earn Magic Points
   - Each tap gives you 1 Magic Point (2 during Rainbow Boost)

2. **Buy Upgrades** ✨
   - Purchase upgrades that automatically generate Magic Points
   - Upgrades become more powerful and expensive as you progress

3. **Use Rainbow Boost** 🌈
   - Activate temporary 2x multiplier for 10 seconds
   - Costs 1,000 Magic Points
   - Perfect for accelerating your progress

4. **Unlock Achievements** 🏆
   - Complete various challenges
   - Reach milestones and earn recognition

5. **Prestige** ⭐
   - Reset your progress when you reach 1,000,000 Magic Points
   - Gain permanent Rainbow Shards
   - Increase your production multiplier for future runs

### Upgrade Tiers

| Tier | Upgrade | Base Cost | Production |
|------|---------|-----------|------------|
| 1 | Magic Horn | 10 | 1/s |
| 2 | Rainbow Mane | 50 | 5/s |
| 3 | Sparkle Hooves | 200 | 20/s |
| 4 | Golden Wings | 1,000 | 100/s |
| 5 | Crystal Horn | 5,000 | 500/s |
| 6 | Starlight Aura | 20,000 | 2,000/s |
| 7 | Galaxy Tail | 100,000 | 10,000/s |
| 8 | Universe Core | 500,000 | 50,000/s |

## 🌍 Multi-language Support

The game supports three languages with auto-detection:

- **English** 🇺🇸 (Default)
- **Russian** 🇷🇺 
- **Belarusian** 🇧🇾

The language is automatically detected from your browser settings, but you can manually change it anytime using the language selector in the navigation.

## 📱 PWA Features

TAP-TAP UNICORN is a Progressive Web App with:

- **Offline Functionality** - Play without internet connection
- **App-like Experience** - Install on your home screen
- **Fast Loading** - Service worker caching for instant loads
- **Cross-platform** - Works on all devices and operating systems

## 🛠️ Technical Details

### Built With

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript** - No frameworks, pure performance
- **PWA Standards** - Service Worker and Web App Manifest

### Browser Support

- Chrome 70+ ✅
- Firefox 65+ ✅
- Safari 12+ ✅
- Edge 79+ ✅
- Mobile browsers ✅

### File Structure


tap-tap-unicorn/
├── index.html              # Main game file
├── manifest.json           # PWA manifest
├── sw.js                   # Service Worker
├── icons/                  # App icons for PWA
│   ├── icon-72x72.png
│   ├── icon-96x96.png
│   ├── icon-128x128.png
│   ├── icon-144x144.png
│   ├── icon-152x152.png
│   ├── icon-192x192.png
│   ├── icon-384x384.png
│   └── icon-512x512.png
└── README.md


## 🎨 Customization

### Themes

The game includes two beautiful themes:

- **Dark Theme** (Default) - Perfect for night gaming sessions
- **Light Theme** - Clean and bright for daytime play

Toggle between themes using the theme switch in the navigation.

### Color Scheme

The game uses a magical color palette:

- Primary: #8A2BE2 (Purple)
- Secondary: #00CED1 (Turquoise)
- Accent: #FF6B6B (Coral)
- Background: #000100 (Near Black)

## 🔧 Development

### Game Architecture

The game is built with a modular architecture:

javascript
// Core Game State
const gameState = {
    score: 0,
    upgrades: [],
    achievements: [],
    prestige: {}
};

// Game Loop
function gameLoop() {
    // Handle passive income
    // Update UI
    // Check achievements
}


### Key Systems

1. **State Management** - LocalStorage for persistence
2. **Rendering Engine** - Dynamic DOM updates
3. **Event System** - Click handlers and game events
4. **Translation System** - Multi-language support
5. **PWA Integration** - Service worker and manifest

### Adding New Features

To add new upgrades:

javascript
{
    id: 9,
    name: "New Upgrade",
    description: "Amazing new feature",
    icon: "⭐",
    baseCost: 1000000,
    baseProduction: 100000,
    count: 0,
    multiplier: 1
}


## 📈 Performance

- **60 FPS Gameplay** - Smooth animations and interactions
- **Memory Efficient** - No memory leaks, optimized garbage collection
- **Fast Loading** - Compressed assets and efficient code
- **Battery Friendly** - Optimized game loop

## 🤝 Contributing

We love contributions! Here's how you can help:

1. **Fork the project**
2. **Create a feature branch** (git checkout -b feature/AmazingFeature)
3. **Commit your changes** (git commit -m 'Add some AmazingFeature')
4. **Push to the branch** (git push origin feature/AmazingFeature)
5. **Open a Pull Request**

### Areas for Contribution

- New upgrades and achievements
- Additional languages
- Visual effects and animations
- Sound design
- Performance optimizations
- Mobile UX improvements

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🏆 Achievements List

| Achievement | Requirement | Reward |
|-------------|-------------|--------|
| First Steps | Reach 100 Magic Points | 🌟 |
| Magic Collector | Reach 1,000 Magic Points | ✨ |
| Rainbow Maker | Reach 10,000 Magic Points | 🌈 |
| Unicorn Tamer | Reach 100,000 Magic Points | 🦄 |
| Star Creator | Reach 1,000,000 Magic Points | ⭐ |
| Galaxy Forger | Reach 10,000,000 Magic Points | 🌌 |
| First Upgrade | Purchase any upgrade | 🔼 |
| Upgrade Master | Purchase 10 upgrades total | 🔝 |
| Rainbow Booster | Activate Rainbow Boost | 🚀 |
| Click Master | Reach 1,000 total clicks | 👆 |
| Prestige Seeker | Prestige for the first time | 🌟 |

## 🔮 Future Plans

- [ ] Sound effects and background music
- [ ] More upgrade tiers
- [ ] Social features and leaderboards
- [ ] Seasonal events
- [ ] Cloud save synchronization
- [ ] VR/AR version
- [ ] Mobile app stores

## 📞 Support

If you need help or have questions:

- **Open an Issue** on GitHub
- **Check Documentation** in the code comments
- **Email Support**: globalygenius@example.com

## 🙏 Acknowledgments

- Inspired by classic clicker games like Cookie Clicker
- Magic icons from Unicode emoji set
- Rainbow color palette from nature's beauty
- Special thanks to the open-source community

---

<div align="center">

**Made with ❤️ and 🦄 magic by [Globaly Genius](https://github.com/globalygenius)**

⭐ **Star this repo if you love magical unicorns!** ⭐

</div>
