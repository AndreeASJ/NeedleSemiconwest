# EISENHOLZ - NeedleSemiconwest v2.0

<div align="center">
  <img src="./assets/branding/eisenholz-logo-n.png" alt="EISENHOLZ Logo" width="300" />
  
  **Interactive 3D Experience for SemiconWest v2.0 powered by Needle Engine**
  
  [![Made with Needle Engine](https://img.shields.io/badge/Made%20with-Needle%20Engine-00D4AA?style=for-the-badge&logo=unity)](https://needle.tools)
  [![Unity](https://img.shields.io/badge/Unity-2022.3.62f2-000000?style=for-the-badge&logo=unity)](https://unity.com)
  [![Three.js](https://img.shields.io/badge/Three.js-0.169.11-000000?style=for-the-badge&logo=three.js)](https://threejs.org)
  [![SemiconWest](https://img.shields.io/badge/Event-SemiconWest-FF6B35?style=for-the-badge)](https://www.semiconwest.org)
</div>

## 🌟 Overview

**NeedleSemiconwest v2.0** is an enhanced immersive 3D interactive experience developed by EISENHOLZ for SemiconWest, showcasing cutting-edge semiconductor technology and industrial equipment. This updated version features improved performance, optimized assets, and enhanced user experience. Built with Unity and exported using Needle Engine, this project demonstrates the power of real-time 3D graphics in modern web browsers for industrial applications.

## 🚀 Live Demo

Experience the interactive 3D world: **[https://andreeasj.github.io/NeedleSemiconwest](https://andreeasj.github.io/NeedleSemiconwest)**

## 🛠️ Technology Stack

- **Unity 2022.3.62f2** - 3D content creation and scene authoring
- **Needle Engine 4.8.9** - Web export and runtime framework
- **Three.js 0.169.11** - WebGL rendering engine
- **GLTF/GLB** - 3D asset format for optimal web delivery
- **WebGL 2.0** - Hardware-accelerated 3D graphics

## 📁 Project Structure

```
NeedleSemiconwest/
├── assets/                    # Compiled 3D assets and resources
│   ├── *.glb                 # 3D models and scenes
│   ├── *.js                  # JavaScript modules
│   ├── *.css                 # Styling
│   └── branding/             # EISENHOLZ branding assets
│       ├── eisenholz-logo-n.png  # EISENHOLZ logo (negative)
│       └── eisenholz-logo-b.png  # EISENHOLZ logo (positive)
├── include/                   # Third-party libraries
│   ├── draco/                # Geometry compression
│   ├── ktx2/                 # Texture compression
│   ├── needle/               # Needle Engine assets
│   └── three/                # Three.js extensions
├── index.html                # Main application entry point
├── needle.buildinfo.json     # Build metadata
├── package.json              # Project configuration
├── README.md                 # This file
├── DEPLOYMENT.md             # Deployment instructions
├── deploy.sh                 # Deployment script
├── CNAME                     # Custom domain configuration
├── _headers                  # Security and CORS headers
└── .github/                  # GitHub Actions workflows
    └── workflows/
        └── deploy.yml        # Automated deployment
```

## 🎮 Features

- **Real-time 3D Rendering** - High-performance WebGL graphics
- **Interactive Elements** - User-controlled 3D navigation
- **Optimized Assets** - Compressed geometry and textures
- **Responsive Design** - Works across desktop and mobile devices
- **Modern Web Standards** - ES6 modules and progressive loading
- **SemiconWest Integration** - Tailored for semiconductor industry showcase

## 🚀 Getting Started

### Prerequisites

- Modern web browser with WebGL 2.0 support
- Local web server (for development)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AndreeASJ/NeedleSemiconwest.git
   cd NeedleSemiconwest
   ```

2. **Serve the files**
   
   **Option A: Using Python**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```
   
   **Option B: Using Node.js**
   ```bash
   npx serve .
   ```
   
   **Option C: Using PHP**
   ```bash
   php -S localhost:8000
   ```

3. **Open in browser**
   Navigate to `http://localhost:8000`

## 🎨 Customization

### Modifying 3D Content

To modify the 3D scene:

1. Open the Unity project in Unity 2022.3.62f2 or later
2. Install the Needle Engine package
3. Make your changes to the scene
4. Export using Needle Engine's build system
5. Replace the generated files in this repository

### Branding

The project uses EISENHOLZ branding throughout:
- Logo files: `assets/branding/eisenholz-logo-n.png` (negative) and `assets/branding/eisenholz-logo-b.png` (positive)
- Favicon: `assets/favicon.8d99ceea.ico`
- Meta tags and titles in `index.html`

## 📱 Browser Compatibility

| Browser | Version | WebGL Support |
|---------|---------|---------------|
| Chrome  | 56+     | ✅ Full       |
| Firefox | 51+     | ✅ Full       |
| Safari  | 15+     | ✅ Full       |
| Edge    | 79+     | ✅ Full       |

## 🔧 Performance Optimization

This project includes several optimization techniques:

- **Geometry Compression** - Draco compression for 3D meshes
- **Texture Compression** - KTX2/Basis Universal for textures
- **Level of Detail (LOD)** - Multiple mesh quality levels
- **Progressive Loading** - Assets load as needed
- **Module Splitting** - Code split for faster initial load

## 📊 Build Information

- **Build Time**: 2025-10-05T22:06:46.026Z
- **Total Size**: ~9.5 MB (optimized from v1.0)
- **Asset Count**: 68 files
- **Compression**: Enhanced compression for all assets
- **Version**: 2.0.0

## 🏭 SemiconWest Integration

This project is specifically designed for SemiconWest, featuring:

- **Industrial Equipment** - Showcase of semiconductor manufacturing equipment
- **Interactive Demonstrations** - Hands-on 3D exploration of complex machinery
- **Educational Content** - Detailed information about semiconductor processes
- **Professional Presentation** - Enterprise-grade visual quality

## 🤝 Contributing

We welcome contributions to improve the NeedleSemiconwest experience:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is developed by EISENHOLZ for SemiconWest. All rights reserved.

## 🔗 Links

- **EISENHOLZ**: [Company Website](https://eisenholz.com)
- **SemiconWest**: [Event Website](https://www.semiconwest.org)
- **Needle Engine**: [https://needle.tools](https://needle.tools)
- **Unity**: [https://unity.com](https://unity.com)
- **Three.js**: [https://threejs.org](https://threejs.org)

## 📞 Support

For technical support or questions about this project, please contact the EISENHOLZ development team.

---

<div align="center">
  <p>Made with ❤️ by <strong>EISENHOLZ</strong> for <strong>SemiconWest</strong></p>
  <p>Powered by <strong>Needle Engine</strong> and <strong>Unity</strong></p>
</div>
