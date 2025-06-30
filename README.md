# 🐦 Bird Migration Visualization

> Interactive map visualization showing bird migration patterns over time using real GPS tracking data.

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=flat-square)](https://dinushitj.github.io/bird-migration-vis/)
[![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-green?style=flat-square)](https://dinushitj.github.io/bird-migration-vis/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)

## 🎯 What It Does

Watch birds migrate across the globe with **smooth animations** and **interactive controls**. This visualization transforms complex GPS tracking data into an intuitive, engaging experience that reveals migration patterns over time.

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| **Interactive Map** | Pan, zoom, and explore real geographic locations |
| **Animation Controls** | Play, pause, restart with custom speed settings |
| **Smart Markers** | Green start → Red path → Red end with popups |
| **Time Display** | Real-time date updates during playback |
| **Customizable Range** | Select any portion of migration data |
| **Fast Performance** | Optimized for smooth experience |

## 🚀 Quick Start

**Try it now:** [dinushitj.github.io/bird-migration-vis](https://dinushitj.github.io/bird-migration-vis/)

### Local Development
```bash
# Clone and run locally
git clone https://github.com/dinushitj/bird-migration-vis.git
cd bird-migration-vis
open index.html  # or python -m http.server 8000
```

## 🎮 How to Use

1. **Start Animation** - Click the play button
2. **Adjust Speed** - Set delay between points (200-500ms recommended)
3. **Set Range** - Choose start point and number of points to display
4. **Explore** - Click markers for direction and timing details
5. **Control** - Use pause/restart as needed

## 🛠️ Built With

- **Frontend:** HTML5, CSS3, JavaScript
- **Mapping:** [Leaflet.js](https://leafletjs.com/) + OpenStreetMap
- **Data:** GPS coordinates from bird tracking research
- **Hosting:** GitHub Pages

## ⚡ Performance Tips

- **Optimal range:** 500-1000 points for best performance
- **Slower speeds:** 300-400ms to clearly see direction changes
- **Browser:** Modern browsers recommended for smooth animations

## 📁 Project Structure

```
bird-migration-vis
├── 📄 index.html     # Main application (all-in-one file)
├── 📊 dataset.js     # GPS tracking data
├── 🎨 favicon.ico    # Site icon
├── 📜 LICENSE        # MIT license
└── 📖 README.md      # You are here
```

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| Slow performance | Reduce point range to 500-1000 |
| Animation choppy | Increase speed delay (400ms+) |
| Map not loading | Check internet connection |

## 🤝 Contributing

Found a bug? Have an idea? 
1. Fork the repo
2. Create a feature branch
3. Commit your changes
4. Submit a pull request

## 📝 License

This project is licensed under the [MIT License](LICENSE) - feel free to use and modify!

## 🌟 Show Your Support

If this project helped you, please ⭐ **star the repository.**

---

<div align="center">

**[🌐 View Live Demo](https://dinushitj.github.io/bird-migration-vis/) | [📖 Documentation](README.md) | [🐛 Report Bug](../../issues)**

</div>
