# Fibonacci Spiral Playground

**Live Demo:** [https://evanmarie.github.io/fibonacci-playground/](https://evanmarie.github.io/fibonacci-playground/)

An interactive 3D visualization exploring the mathematical beauty of the Fibonacci spiral and phyllotaxis patterns found throughout nature. Experience the golden ratio in action through dynamic animations and real-time parameter control.

![Fibonacci Spiral Preview](https://via.placeholder.com/800x400/131924/e2e8f0?text=Fibonacci+Spiral+Visualization)

## ✨ Features

### 🎮 Interactive Controls
- **Mouse Controls**: Drag to rotate, scroll to zoom
- **Real-time Sliders**: Adjust radius, depth, node count, zoom, and animation speed
- **Dynamic Animations**: Breathing, spinning, and node count animations
- **Number Display**: Toggle Fibonacci numbers on spiral nodes (up to 4 digits)

### 🔬 Mathematical Accuracy
- Implements the **Golden Angle** (137.508°) for optimal packing
- Follows **Phyllotaxis** principles found in sunflowers, pinecones, and galaxies
- Demonstrates **scale invariance** from microscopic to cosmic structures
- Shows emergent **Fibonacci sequences** in spiral arm patterns

### 🎨 Visual Design
- Modern dark theme with vibrant gradient tubes
- Smooth animations with customizable speed control
- Responsive design that scales across all devices
- Professional 3D rendering with Three.js

## 🚀 Quick Start

### Online
Simply visit [https://evanmarie.github.io/fibonacci-playground/](https://evanmarie.github.io/fibonacci-playground/) and start exploring!

### Local Development
```bash
git clone https://github.com/evanmarie/fibonacci-playground.git
cd fibonacci-playground
# Open index.html in your browser - no build required!
```

## 🎯 How to Use

### Basic Navigation
- **Drag** with mouse to rotate the spiral
- **Scroll** to zoom in/out
- **Adjust sliders** to modify the spiral's appearance in real-time

### Control Panel
| Control | Description |
|---------|-------------|
| **Radius** | Changes the overall size of the spiral |
| **Depth** | Transforms from 2D to 3D cone structure |
| **Nodes** | Number of points in the spiral (6-500) |
| **Zoom** | Camera distance from the spiral |
| **Speed** | Animation playback speed |

### Animations
- **🫁 Breathe**: Rhythmic expansion/contraction
- **🌀 Spin**: Clockwise rotation around the spiral axis
- **🔢 Count**: Animated growth from 1 to 500 nodes
- **👁 Numbers**: Display Fibonacci numbers on nodes

### Keyboard Shortcuts
- `i` - Open information modal
- `r` - Reset all parameters
- `b` - Toggle breathing animation
- `s` - Toggle spinning animation
- `c` - Toggle node count animation
- `n` - Toggle number display
- `Esc` - Close modal

## 🧮 The Mathematics

### Golden Angle
The spiral uses the golden angle of **137.508°** between each point, derived from:
```
Golden Angle = 360° / φ² ≈ 137.508°
```
Where φ (phi) is the golden ratio ≈ 1.618

### Spiral Equation
Each point is positioned using:
```
θ = n × 137.508°
r = k√n
```
- **θ**: Angular position using golden angle
- **r**: Radial distance grows as square root of position
- **n**: Point number in sequence

### Fibonacci Connection
Although generated purely with the golden angle, the spiral naturally exhibits Fibonacci number patterns in its visible spiral arms - a beautiful example of mathematical emergence.

## 🌿 Natural Examples

This pattern appears throughout nature:
- **Plants**: Sunflower seed arrangements, pinecone scales, flower petals
- **Marine**: Nautilus shell chambers, spiral coral growth
- **Cosmic**: Galaxy spiral arms, hurricane formations
- **Microscopic**: DNA helix structure, virus arrangements

## 🛠 Technical Details

### Built With
- **Three.js r128** - 3D graphics and rendering
- **Vanilla JavaScript** - No frameworks, pure performance
- **CSS3** - Responsive design with vh units
- **HTML5 Canvas** - High-performance rendering

### Performance Optimizations
- Efficient geometry creation with reduced polygon counts
- Optimized animation loops running at 60fps
- Smart visibility culling for better performance
- Memory-efficient spiral generation

### Browser Compatibility
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- 📱 Mobile browsers supported

## 🎓 Educational Use

Perfect for:
- **Mathematics Education**: Demonstrating golden ratio and Fibonacci sequences
- **Biology Classes**: Showing phyllotaxis in plant growth
- **Art & Design**: Exploring natural proportions and patterns
- **Computer Science**: 3D graphics and mathematical visualization

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Report bugs or suggest features via [Issues](https://github.com/evanmarie/fibonacci-playground/issues)
- Submit pull requests for improvements
- Share educational use cases

### Development Setup
No build process required! Simply:
1. Fork the repository
2. Edit `index.html` directly
3. Test in your browser
4. Submit a pull request

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Inspired by the mathematical work on phyllotaxis and the golden ratio
- Three.js community for excellent 3D graphics tools
- Nature's incredible mathematical patterns that inspire us all

## 📞 Contact

- **GitHub**: [@evanmarie](https://github.com/evanmarie)
- **Project**: [Fibonacci Playground](https://github.com/evanmarie/fibonacci-playground)

---

*"In mathematics, the art of proposing a question must be held of higher value than solving it."* - Georg Cantor

Explore the mathematical beauty of nature at [https://evanmarie.github.io/fibonacci-playground/](https://evanmarie.github.io/fibonacci-playground/)
