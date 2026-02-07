# Bridge Modes Calculator

A simple, offline-friendly bridge scoring calculator supporting **Chicago Bridge**, **Bonus Bridge**, and **Bonus Bridge Lite**.

## 🎮 Live Demo

[Play Now on GitHub Pages](https://YOUR-USERNAME.github.io/bridge-modes-app/)

## 📱 Features

- **Fully Offline** - Works without internet connection (perfect for cruises!)
- **Mobile Optimized** - Touch-friendly interface for phones and tablets
- **Stay Awake Mode** - Prevents screen from sleeping during play
- **Three Game Modes:**
  - **Chicago Bridge** - Traditional 4-deal cycle with automatic vulnerability
  - **Bonus Bridge** - Innovative HCP-based scoring that rewards both declarers and defenders
  - **Bonus Bridge Lite** - Simplified version with easier calculations

## 🎯 Game Modes

### Chicago Bridge
Classic bridge with a structured 4-deal vulnerability cycle:
- Deal 1: None Vulnerable
- Deal 2: North-South Vulnerable  
- Deal 3: East-West Vulnerable
- Deal 4: Both Vulnerable

Standard bridge scoring applies. Perfect for traditional players.

### Bonus Bridge (Full)
An innovative scoring system that:
- Rewards both declarers AND defenders on every hand
- Adjusts scores based on HCP and distribution
- Makes games fairer - good play matters more than good cards
- Considers contract difficulty and hand strength

Features:
- HCP-based expectations for each contract level
- Distribution analysis (helps suit contracts, hurts NT)
- Defender rewards for limiting declarer's tricks
- Performance-based bonuses

### Bonus Bridge Lite
Simplified version of Bonus Bridge:
- Fewer calculation steps
- Easier mental math
- Fixed defender rewards (2-4 points)
- No distribution penalties
- Perfect for beginners or casual play

## 🚀 Quick Start

### Option 1: Use GitHub Pages (Easiest)
1. Visit the live demo link above
2. Add to your phone's home screen for app-like experience

### Option 2: Download for Offline Use
1. Download `index.html` from this repository
2. Open it in any web browser (Chrome, Safari, Firefox, etc.)
3. Works completely offline - no internet needed!

### Option 3: Run Locally
```bash
git clone https://github.com/YOUR-USERNAME/bridge-modes-app.git
cd bridge-modes-app
# Open index.html in your browser
```

## 📖 How to Use

1. **Select Mode** - Choose Chicago, Bonus Bridge, or Bonus Bridge Lite
2. **Enter Contract** - Select level (1-7), suit, declarer, and doubling
3. **Enter Result** - Made exactly, plus overtricks, or down
4. **For Bonus Modes** - Enter declarer's HCP and distribution
5. **View Score** - See points awarded to both sides
6. **History** - Review all hands played with detailed scoring

## 🎲 Bonus Bridge Philosophy

Traditional bridge scoring only rewards the declaring side. This creates an imbalance when one partnership holds better cards throughout the session.

**Bonus Bridge solves this by:**
- Giving defenders points even when contracts make
- Rewarding declarers who make contracts with weak hands
- Penalizing declarers who fail with strong hands
- Making distribution matter (shape helps suit contracts, hurts NT)

The result: **Skill matters more than card luck!**

## 📊 Score Scaling

Both Bonus Bridge modes use improved score scaling (raw score ÷ 15) to create more balanced games:
- Part scores: ~5-10 points
- Games: ~25-35 points  
- Slams: ~60-100+ points

Defenders consistently earn 1-4 points per hand, keeping games competitive.

## 🛠️ Technical Details

- **Single HTML file** - No external dependencies
- **Pure JavaScript** - No frameworks required
- **Wake Lock API** - Keeps screen on during play (supported on modern mobile browsers)
- **Progressive Web App ready** - Can be installed on mobile
- **Works offline** - All code is embedded
- **Responsive design** - Adapts to any screen size

## 📱 Mobile Installation

### iOS (Safari)
1. Open the app in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add"

### Android (Chrome)
1. Open the app in Chrome
2. Tap the menu (three dots)
3. Tap "Add to Home Screen"
4. Tap "Add"

## 🎓 About the Creator

Created by **Mike Smith**, an experienced bridge player with 40 years of play. The Bonus Bridge scoring system was developed to address the fundamental fairness issues in traditional bridge scoring, where defenders receive no recognition for good defense when contracts make.

## 📝 Version History

### v1.0 (February 2026)
- Initial release with three game modes
- Full offline support
- Mobile-optimized interface
- Comprehensive help system
- History tracking with detailed scoring breakdown

## 🤝 Contributing

Suggestions and improvements welcome! This app was designed for bridge players by bridge players.

## 📄 License

Free to use for personal and club play. 

## 🐛 Known Issues

None currently. If you find a bug, please report it!

## 💡 Tips for Best Experience

- **Activate "Stay Awake" mode** to prevent screen timeout during play
- Use in landscape mode on phones for easier button access
- Enable "Add to Home Screen" for offline access
- Review the Help popup for each mode before playing
- Try Bonus Bridge Lite first to learn the system
- Check History regularly to verify scoring accuracy

## 🎯 Future Enhancements

Possible future additions:
- Export game results to PDF/CSV
- Multiple player profiles
- Tournament mode with Swiss pairing
- Statistical analysis of games played
- Cloud sync (optional) for multi-device access

---

**Enjoy your bridge games! May your finesses work and your slams make!** 🃏♠️♥️♦️♣️
