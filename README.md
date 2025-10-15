# My Living Map 🗺️

A dynamic, interactive vintage map that simulates historical trade routes with animated ships and real-time seasonal weather effects.

## ✨ Features

- **Animated Trade Routes**: Watch ships traverse the Atlantic and Indian Ocean along historical trade paths
- **Seasonal Weather System**: Real-time weather changes based on the current month
  - Winter storms in the North Atlantic (October - March)
  - Tropical cyclones during summer months (April - September)
  - Snow effects over northern continents in winter
  - Rain and storm effects in storm zones
- **Dynamic Water Effects**: Animated wave patterns that intensify during storms
- **Ship Wake Trails**: Ships leave realistic wake patterns as they travel
- **Vintage Aesthetic**: Old-world map styling with sepia tones and classic maritime design

## 🚀 Demo

**[View Live Demo](https://anacondy.github.io/my-living-map/)**

## 🛠️ Technology

This project is built with pure vanilla JavaScript, HTML5 Canvas, and CSS3:
- No external libraries or dependencies
- All assets embedded as base64 data URIs for portability
- Responsive canvas animations using `requestAnimationFrame`
- CSS animations for ship movements and storm effects

## 📖 How It Works

The map features two ships following pre-defined trade routes:
1. **Ship 1**: Atlantic route (Europe → Mid-Atlantic → Caribbean → South Atlantic → South Africa)
2. **Ship 2**: Indian Ocean route (South Africa → Indian Ocean → Near Australia → Southern Ocean)

The weather engine automatically:
- Detects the current month
- Activates appropriate seasonal weather patterns
- Generates particle effects (rain, snow, ship wakes)
- Animates cyclones during summer months
- Creates storm effects when ships enter winter storm zones

## 🎮 Usage

Simply open the `index.html` file in a modern web browser, or visit the live demo link above. The map will automatically:
- Display the current month
- Show appropriate weather conditions
- Animate ships along their trade routes
- Update effects in real-time

## 🌍 Browser Compatibility

Works best in modern browsers with HTML5 Canvas support:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

## 📜 License

This project is available under the terms specified in the [LICENSE](LICENSE) file.

## 🤝 Contributing

Feel free to fork this project and submit pull requests with improvements or new features!

## 📸 Preview

The map displays a vintage cartographic style with animated elements including moving ships, weather particles, and seasonal cyclones. The info panel in the top-left corner shows the current month and weather status.

---

*Created as a demonstration of canvas-based animations and seasonal weather simulation*