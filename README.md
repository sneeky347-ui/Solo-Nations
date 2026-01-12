# 🏴 Solo Nations

> Build. Expand. Dominate. Lead your nation to greatness in this immersive idle nation-building game.

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)
![Three.js](https://img.shields.io/badge/Three.js-r128-black.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

**[Play Now](https://solonations.pythonanywhere.com)** • **[Documentation](https://solonations.pythonanywhere.com/documentation.html)** • **[Report Bug](https://github.com/yourusername/solo-nations/issues)**

</div>

---

## 📖 About

**Solo Nations** is a browser-based multiplayer idle/incremental nation-building game where you lead your own country from a humble settlement to a thriving superpower. Watch your nation grow in real-time with stunning 3D visualizations, compete on global leaderboards, and expand your territory through strategic plot acquisitions.

### ✨ Key Features

- 🗺️ **3D Nation Visualization** - Watch your nation grow with beautiful 3D buildings rendered using Three.js
- 🏗️ **Progressive Building System** - Unlock and construct 7+ unique building types
- 📈 **Idle Progression** - Earn resources even while you're away
- 🏆 **Global Leaderboards** - Compete with players worldwide
- 💰 **Plot Expansion** - Purchase and unlock new territories to expand your nation
- ⚡ **Boost System** - Activate temporary income multipliers
- 🎨 **Modern Glassmorphic UI** - Sleek, contemporary design with smooth animations

---

## 🎮 Game Mechanics

### 💵 Resources

| Resource | Icon | Description |
|----------|------|-------------|
| **Money** | 💰 | Primary currency for purchasing buildings and plots |
| **Population** | 👥 | Citizens living in your nation |
| **Production** | 🏭 | Industrial output of your nation |
| **Energy** | ⚡ | Power generation capacity |

### 🏢 Buildings

Buildings generate passive income and grow more expensive with each purchase:

```
🏘️ Residential Homes    →  Base Income: $1/s
🌾 Farms                 →  Base Income: $5/s  
⛏️ Mines                 →  Base Income: $20/s (Unlock: $1K)
💡 Power Plants          →  Base Income: $50/s (Unlock: $5K)
🏢 Office Buildings      →  Base Income: $100/s (Unlock: $15K)
🏭 Factories             →  Base Income: $500/s (Unlock: $50K)
🏫 Schools               →  Base Income: $1,000/s (Unlock: $100K)
```

### 🗺️ Territory Expansion

Expand your nation across a 3×3 grid of plots:

| Plot | Cost | Status |
|------|------|--------|
| Plot 1 | Free | Starting Territory |
| Plot 2 | $5K | Locked |
| Plot 3 | $10K | Locked |
| Plot 4 | $25K | Locked |
| Plot 5 | $50K | Locked |
| Plot 6 | $100K | Locked |
| Plot 7 | $250K | Locked |
| Plot 8 | $500K | Locked |
| Plot 9 | $1M | Locked |

### 🎯 Actions

- **💰 Collect Taxes** - Click to generate instant income
- **⚡ Boost** - Activate 2x income multiplier for 30 seconds (60s cooldown)
- **🎁 Offline Earnings** - Collect accumulated income while you were away

---

## 🚀 Getting Started

### Play the Game

Simply visit **[solonations.pythonanywhere.com](https://solonations.pythonanywhere.com)** in your browser!

### Prerequisites

- Modern web browser with WebGL support (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Stable internet connection

### First Steps

1. **Create an Account** - Sign up with username and password
2. **Name Your Nation** - Choose a unique name for your country
3. **Start Building** - Purchase your first homes and farms
4. **Expand Territory** - Buy new plots as you earn money
5. **Climb the Leaderboard** - Compete with players worldwide!

---

## 🎨 Technology Stack

### Core Technologies

- **JavaScript ES6+** - Game logic & mechanics
- **Three.js (r128)** - 3D rendering engine for nation visualization
- **HTML5 & CSS3** - Modern UI design with glassmorphic effects
- **Canvas API** - High-performance rendering
- **WebGL** - Hardware-accelerated 3D graphics

### Design Features

- **CSS Grid & Flexbox** - Responsive layouts
- **CSS Animations** - Smooth transitions and effects
- **Backdrop Filter** - Glassmorphic design elements
- **Custom Shaders** - Dynamic lighting and shadows

---

## 📁 Repository Information

This repository contains **select open-source components** from Solo Nations:

### 🔓 Open Source Components

```
solo-nations-public/
│
├── 3d-rendering/
│   ├── building-generator.js   # 3D building mesh generation
│   ├── plot-system.js           # Territory plot rendering
│   └── camera-controls.js       # Camera movement system
│
├── ui-components/
│   ├── glassmorphic-cards.css  # Reusable card components
│   └── animations.css           # UI animation library
│
└── examples/
    ├── basic-building-demo.html
    └── plot-expansion-demo.html
```

### 🔒 Proprietary Components

The core game logic, server architecture, multiplayer systems, and gameplay mechanics remain **closed source** to protect the integrity of the game experience.

---

## 📚 Documentation

For complete documentation, visit:

**[solonations.pythonanywhere.com/documentation.html](https://solonations.pythonanywhere.com/documentation.html)**

### Documentation Sections

- **🎮 Gameplay Guide** - Learn all game mechanics
- **🏗️ Building Strategies** - Optimize your nation's growth
- **🗺️ Territory Management** - Master plot expansion
- **🏆 Leaderboard Tips** - Climb to the top
- **⚡ Advanced Techniques** - Pro player strategies
- **❓ FAQ** - Common questions answered
- **🔧 Technical Specs** - Browser requirements and performance

---

## 🎯 Roadmap

### Version 1.1 (Coming Soon)

- [ ] Multiplayer trading system
- [ ] Alliance/guild system
- [ ] Achievement system
- [ ] Sound effects and music
- [ ] Mobile responsive design

### Version 1.2 (Future)

- [ ] Prestige/revolution system
- [ ] Technology research tree
- [ ] Random events (disasters, booms)
- [ ] Seasonal competitions
- [ ] Save/load to cloud backup

### Version 2.0 (Vision)

- [ ] Diplomacy system
- [ ] War mechanics
- [ ] Custom nation flags and emblems
- [ ] Historical eras progression
- [ ] Multiplayer real-time battles

---

## 🤝 Contributing to Open Components

While the full game is proprietary, we welcome contributions to our open-source components!

### How to Contribute

1. **Fork** this repository
2. **Create** a feature branch (`git checkout -b feature/ImprovementName`)
3. **Commit** your changes (`git commit -m 'Improve 3D rendering performance'`)
4. **Push** to the branch (`git push origin feature/ImprovementName`)
5. **Open** a Pull Request

### Contribution Guidelines

- Focus on the open-source 3D rendering and UI components
- Follow existing code style and conventions
- Test your changes thoroughly in multiple browsers
- Update component documentation as needed
- Keep commits atomic and well-described

### What Can Be Contributed

✅ **Accepted Contributions:**
- Performance optimizations for 3D rendering
- New building mesh designs
- UI/UX improvements for components
- Animation enhancements
- Browser compatibility fixes
- Documentation improvements

❌ **Not Accepted:**
- Core game logic modifications
- Balance changes
- Multiplayer system alterations
- Server-side code

---

## 🐛 Bug Reports

Found a bug in the open-source components? Please open an issue with:

- **Description** - What happened?
- **Steps to Reproduce** - How can we recreate it?
- **Expected Behavior** - What should happen?
- **Screenshots** - Visual evidence helps!
- **Browser/OS** - Your environment details
- **Component** - Which open-source component is affected?

For bugs in the main game, please report through the in-game feedback system.

---

## 📊 Game Statistics

### Progression Tiers

```
Tier 1: Settlement      →  $0 - $10K
Tier 2: Town            →  $10K - $100K  
Tier 3: City            →  $100K - $1M
Tier 4: Regional Power  →  $1M - $10M
Tier 5: Nation          →  $10M - $100M
Tier 6: Superpower      →  $100M+
```

### Building Efficiency

| Building Type | Cost Multiplier | Efficiency Rating |
|---------------|-----------------|-------------------|
| Homes | 1.15x | ⭐⭐ |
| Farms | 1.15x | ⭐⭐ |
| Mines | 1.15x | ⭐⭐⭐ |
| Power Plants | 1.15x | ⭐⭐⭐ |
| Offices | 1.15x | ⭐⭐⭐⭐ |
| Factories | 1.15x | ⭐⭐⭐⭐ |
| Schools | 1.15x | ⭐⭐⭐⭐⭐ |

---

## 🎮 Tips & Strategies

> **Pro Tips for New Players:**

1. 💡 **Early Game** - Focus on Homes and Farms for steady income
2. 🎯 **Mid Game** - Unlock Mines and Power Plants as soon as possible
3. 🚀 **Late Game** - Maximize Factories and Schools for exponential growth
4. 🗺️ **Plot Strategy** - Only buy new plots when you can fill them with buildings
5. ⚡ **Boost Timing** - Use boosts when you have maximum income per second
6. 🏆 **Leaderboard** - Consistent play beats sporadic bursts

---

## 📞 Contact & Support

### Game Support

- **In-Game Feedback** - Use the feedback button in settings
- **Documentation** - [solonations.pythonanywhere.com/documentation.html](https://solonations.pythonanywhere.com/documentation.html)
- **Email** - support@solonations.com

### Open Source Component Issues

- **GitHub Issues** - For bugs in open-source components
- **Pull Requests** - For improvements to public code

---

## 📜 License

### Open Source Components

The 3D rendering system and UI components in this repository are licensed under the MIT License.

```
MIT License - Open Source Components Only

Copyright (c) 2025 Solo Nations

Permission is hereby granted, free of charge, to any person obtaining a copy
of the open-source components of this software...
```

### Proprietary Game Code

The core game logic, server infrastructure, and gameplay systems are proprietary and **not open source**. All rights reserved.

---

## 👥 Credits

### Development

- **Game Design & Development** - Solo Nations Team
- **3D Graphics Engine** - Three.js Community
- **UI/UX Design** - Modern Glassmorphism Inspired

### Special Thanks

- The Three.js community for excellent documentation
- All playtesters and early supporters
- Players who provide valuable feedback
- Open source contributors

### Inspiration

- SimCity series for city-building mechanics
- Cookie Clicker for incremental gameplay
- AdVenture Capitalist for idle progression
- Civilization series for nation management

---

## 📈 Community

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/yourusername/solo-nations?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/solo-nations?style=social)

**Join thousands of players building their nations!**

</div>

---

<div align="center">

### 🌟 Star this repo if you enjoy the open-source components! 🌟

**[Play Now](https://solonations.pythonanywhere.com)** • **[Documentation](https://solonations.pythonanywhere.com/documentation.html)** • **[Report Bug](https://github.com/yourusername/solo-nations/issues)**

**Made with ❤️ and JavaScript**

**[⬆ Back to Top](#-solo-nations)**

</div>
