# 🚀 Navaneeth M - 3D Portfolio (Outer Site)

An immersive 3D web experience built with **Three.js** and **TypeScript**. This project serves as the interactive "Hardware" layer of my portfolio, featuring a realistic 3D desk setup that hosts a fully functional web-based OS inside the monitor.

## 🚀 Live Demo
[Explore the 3D World](https://navaneethm.com/) (Link to your final deployment)

## ✨ Features
- **Interactive 3D Scene:** A highly detailed 3D room environment built with Three.js.
- **OS Integration:** Projected "Inner Site" via `CSS3DRenderer` using iframe occlusion techniques.
- **Dynamic Camera:** Cinematic transitions between "Idle", "Desk", and "Monitor" views powered by `TWEEN.js`.
- **Baked Lighting:** High-fidelity visuals optimized for the web using baked textures and ambient occlusion maps.
- **Interactive Objects:** Clickable 3D hitboxes that trigger camera movements and OS interactions.
- **Spatial Audio:** Immersive sound effects for environment atmosphere and hardware interaction.

## 🛠️ Tech Stack
- **Engine:** Three.js / WebGL
- **Language:** TypeScript
- **Bundler:** Webpack 5
- **Animations:** GSAP & Tween.js
- **UI Overlay:** React 17 (Loading screen and interface controls)
- **Deployment:** Vercel

## 📂 Key Directory Structure
- `src/Application/`: Main engine and scene orchestration.
- `src/Application/World/`: 3D object definitions (Computer, Coffee, Environment).
- `src/Application/Camera/`: Camera keyframes and transition management.
- `static/models/`: GLB assets and baked texture maps.

## 🚀 Getting Started
1. **Clone the repository:**
   ```bash
   git clone https://github.com/navaneeth-0930/Portfolio.git
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Run the local dev server:**
   ```bash
   npm run dev
   ```
4. **Build for production:**
   ```bash
   npm run build
   ```

---
Developed by [Navaneeth M](https://github.com/navaneeth-0930)
