# WebXR Modern University Classroom

A virtual reality classroom environment built with A-Frame, featuring a modern university classroom with interactive elements and immersive WebXR support.

## Features

- 🏫 **Large-scale classroom**: 40x30 meters spacious learning environment
- 🪑 **Diverse seating**: 40+ seats including sofas, modern chairs, bean bags, and high tables
- 💡 **Enhanced lighting**: Multiple light sources for optimal visibility
- 📚 **Educational elements**: Bookshelves, presentation area with large screen
- 🌟 **Colorful design**: Vibrant furniture with varied color schemes
- 🔒 **HTTPS server**: Secure connection for WebXR compatibility
- 📱 **Cross-platform**: Works on VR headsets, mobile devices, and desktop browsers

## Quick Start

### Prerequisites

- Node.js (v14 or higher)
- Modern web browser with WebXR support (Chrome, Firefox, Edge)
- VR headset (optional, for full VR experience)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/RNMUDS/webxr-make-room-test.git
cd webxr-make-room-test
```

2. Install dependencies:
```bash
npm install
```

3. Start the HTTPS server:
```bash
node server.js
```

4. Open your browser and navigate to:
```
https://localhost:3000
```

**Note**: You may need to accept the self-signed certificate warning in your browser.

## Usage

### Desktop/Mobile
- **Mouse/Touch**: Look around by clicking and dragging
- **WASD keys**: Move around the classroom
- **Arrow keys**: Alternative movement controls

### VR Mode
- Click the VR goggles icon in the bottom-right corner to enter VR mode
- Use VR controllers to teleport and interact within the environment

## Classroom Layout

The virtual classroom includes:

- **Front Area**: Large presentation screen and platform for lectures
- **Seating Areas**: 
  - 8 comfortable sofas (front and side areas)
  - 32 modern chairs (center section in organized rows)
  - 28 bean bags (casual seating area)
  - 12 high tables with stools (collaborative workspace)
- **Study Resources**: Wall-mounted bookshelves with multiple sections
- **Ambient Elements**: Plants, coffee station, and decorative items
- **Lighting**: Comprehensive lighting system for optimal visibility

## Technical Details

### Built With
- [A-Frame](https://aframe.io/) - Web framework for building VR experiences
- [Express.js](https://expressjs.com/) - Web server framework
- Node.js - Runtime environment
- HTTPS - Secure connection for WebXR features

### File Structure
```
webxr-make-room-test/
├── public/
│   └── index.html          # Main A-Frame scene
├── server.js               # HTTPS server configuration
├── server.key              # SSL private key
├── server.cert             # SSL certificate
├── package.json            # Node.js dependencies
└── README.md              # This file
```

### WebXR Compatibility

This application supports:
- **Immersive VR**: Full VR headset experience
- **Immersive AR**: Augmented reality on supported devices
- **Inline**: Standard web browser viewing

## Development

### Customizing the Classroom

The classroom layout is defined in `public/index.html`. Key sections include:

- **Room Structure**: Floor, walls, ceiling dimensions
- **Lighting**: Ambient and point lights configuration
- **Furniture**: Positions, colors, and materials of all classroom elements
- **Camera**: Starting position and movement controls

### Adding New Elements

To add new furniture or decorative elements:

1. Add A-Frame entities to the scene in `index.html`
2. Set appropriate positions, materials, and colors
3. Test in both desktop and VR modes

### Server Configuration

The HTTPS server is required for WebXR features. The included SSL certificates are self-signed for development purposes. For production, use proper SSL certificates.

## Browser Support

- Chrome 79+ (recommended for VR)
- Firefox 70+
- Safari 13+ (limited WebXR support)
- Edge 80+

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- [A-Frame](https://aframe.io/) community for the excellent WebXR framework
- WebXR standards for enabling immersive web experiences
- Modern classroom design inspiration for creating an engaging learning environment

---

**Enjoy exploring the virtual classroom! 🎓**