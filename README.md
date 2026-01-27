# 🎮 Tabou - EisatoponAI

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red.svg)](https://eisatopon.gr)

> Viral word guessing game with 310 professionally curated cards across 10 diverse categories. Built with vanilla JavaScript for instant play—no installation required!

🎯 **[Play Live Demo](#)** | 📝 **[View on Eisatopon.gr](https://eisatopon.gr)**

---

## ✨ Features

- 🎴 **310 Premium Cards** - Professionally crafted across 10 categories
- 🎨 **Beautiful Design** - Classic board game aesthetic with modern UX
- 📱 **Mobile Optimized** - Responsive design for all devices
- ⚡ **Instant Play** - No downloads, no installation
- 🎯 **10 Categories**:
  - 🎬 Cinema & Movies
  - 🎵 Music (with golden note ♪)
  - ⚽ Sports
  - 🌍 Geography & Travel
  - 🍔 Food
  - 💻 Tech
  - 🦁 Animals & Nature
  - 🏛️ History
  - 📺 Greek TV & Series
  - ⚗️ Science
- 🎲 **Mixed Mode** - Random cards from all categories
- 👥 **Team Mode** - Score tracking for Team A & Team B
- ⏱️ **60-Second Timer** - Perfect game pacing
- 🔄 **Auto-Shuffle** - Endless gameplay

---

## 🎯 How to Play

**Tabou** (Taboo) is a classic word-guessing party game:

1. **Choose a category** from 10 options
2. **One player describes** the main word to their team
3. **Can't use** any of the 5 forbidden words shown on the card
4. **Team guesses** before time runs out (60 seconds)
5. **Score points** for correct answers!

Perfect for:
- 🎉 Parties
- 👨‍👩‍👧‍👦 Family game nights
- 🎓 Educational activities
- 🏢 Team building

---

## 🚀 Quick Start

### Option 1: Direct Play
Simply download `tabou-app.html` and open it in any modern browser!

### Option 2: Host on Your Website
```bash
# Download the file
wget https://raw.githubusercontent.com/Eisatopon/tabou-eisatopon/main/tabou-app.html

# Upload to your web server
# That's it! No dependencies needed.
```

### Option 3: GitHub Pages (Free Hosting)
1. Fork this repository
2. Go to Settings → Pages
3. Select `main` branch
4. Your game will be live at: `https://yourusername.github.io/tabou-eisatopon/tabou-app.html`

---

## 💻 Tech Stack

- **HTML5** - Structure
- **CSS3** - Styling with gradients & animations
- **Vanilla JavaScript** - Zero dependencies
- **Progressive Web App Ready** - Can be installed as an app

**Browser Support:**
- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers

---

## 🎨 Design Philosophy

- **Classic Board Game Aesthetic** - Inspired by the original Tabou/Taboo
- **Professional Color Palette** - Carefully selected for maximum readability
- **Soft Rainbow Gradient Background** - Fun without being overwhelming
- **Responsive & Accessible** - Works on all screen sizes

---

## 📦 What's Inside

```
tabou-app.html          # Complete game (all-in-one file)
├── Embedded CSS        # Styling & animations
├── Embedded JavaScript # Game logic
└── 310 Cards Database  # All categories & cards
```

**File Size:** ~50KB (lightning fast!)

---

## 🎯 Categories Overview

| Category | Cards | Icon | Color |
|----------|-------|------|-------|
| Cinema | 40 | 🎬 | Deep Red |
| Music | 30 | ♪ | Purple (gold note) |
| Sports | 30 | ⚽ | Green |
| Geography | 20 | 🌍 | Gold |
| Food | 20 | 🍔 | Mustard Yellow |
| Tech | 30 | 💻 | Blue |
| Animals & Nature | 30 | 🦁 | Teal |
| History | 30 | 🏛️ | Deep Olive |
| Greek TV & Series | 30 | 📺 | Electric Blue |
| Science | 30 | ⚗️ | Turquoise |

---

## 🛠️ Customization

Want to add your own cards or categories? The game database is embedded in the HTML file. Simply:

1. Open `tabou-app.html` in a text editor
2. Find the `tabouCards` object (around line 500)
3. Add your custom cards following the format:
```javascript
{ word: "YourWord", forbidden: ["word1", "word2", "word3", "word4", "word5"] }
```

---

## 📱 PWA Installation

Users can install this game as a Progressive Web App:

1. Open the game in Chrome/Edge (mobile or desktop)
2. Click the menu (⋮)
3. Select "Install app" or "Add to Home Screen"
4. Enjoy offline play!

---

## 🤝 Contributing

Contributions are welcome! Ideas for improvement:

- [ ] Additional language support
- [ ] Custom card creator
- [ ] Online multiplayer
- [ ] Leaderboard system
- [ ] Sound effects
- [ ] More categories

Feel free to open an issue or submit a pull request!

---

## 📄 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2026 Eisatopon

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🌟 Credits

**Created with ❤️ by [Eisatopon](https://eisatopon.gr)**

Powered by **EisatoponAI** - Because great games deserve great AI assistance!

---

## 📞 Contact

- 🌐 Website: [eisatopon.gr](https://eisatopon.gr)
- 📧 Questions? Open an issue on GitHub!

---

<div align="center">

**⭐ Star this repo if you enjoyed the game! ⭐**

Made in Greece 🇬🇷 | Built with Vanilla JS 💛

</div>
