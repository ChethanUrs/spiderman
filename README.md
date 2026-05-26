# 🕷️ Spidey-Verse HUD Multiverse Dashboard & Interactive Experience

Welcome to the **Spider-Man Multiverse Portfolio** of **Rohit U** — an ultra-modern, high-end WebGL HUD (Heads-Up Display) dashboard. Built as a zero-build, self-contained single-page application using vanilla HTML, CSS, and modern CDN animation libraries, this experience fuses Marvel's iconic *Spider-Verse* cinematic style with high-tech cyberpunk aesthetics and interactive Web Audio API synthesis.

🔗 **Live Local Preview**: [http://localhost:8080](http://localhost:8080)  
🏫 **Academic Profile**: BCA / Integrated MCA Student at Amrita Vishwa Vidyapeetham, Mysuru Campus.

---

## 🚀 Cinematic Technologies & Architecture

To maintain zero-install portability and extreme performance, the project avoids complex node bundlers and relies on high-speed animation engines loaded via secure CDNs:

1. **Three.js (r128)**: Renders a real-time, hardware-accelerated 3D coordinate space overlay on the viewport, representing the multi-dimensional spider-web mesh and glowing parallax environments.
2. **GSAP (GreenSock) + ScrollTrigger**: Automates all scroll-based timelines, staggered item entry, elastic spring easing curves, and complex SVG path sweeps.
3. **Lenis (Studio Freight)**: Drives ultra-smooth, lightweight inertial smooth scrolling across trackpads, scroll wheels, and touch devices, synchronized directly with GSAP's physics tickers.
4. **Web Audio API Synth Engine**: Synthesizes low-latency sci-fi wind sweeps, elastic thwip pulls, metallic crashes, and high-frequency FM "Spider-Sense" tingle alerts programmatically in real-time.

---

## 🎨 Immersive Design System

- **Holographic Neon Palette**: Deep midnight blacks (`#060610`), vibrant portal electric blues (`#00d2ff`), and high-energy neon spider reds (`#ff003c`).
- **Cyber Scanline Overlay**: A full-viewport transparent halftone comic grid and scanline mesh that sweeps downwards repeatedly.
- **HUD Glassmorphism**: Cards and Address Panels styled as glowing frosted panels using `backdrop-filter: blur(12px) saturate(180%)` with electric cyan corner brackets and blinking active telemetry readings (`SYS.TELEMETRY: ACTIVE`).

---

## ⚡ Suite of 15 Advanced Cinematic & Micro-Animations

The portfolio is loaded with rich interactive layers designed to make the experience feel reactive and alive:

1. **Aiming HUD Reticle Tracker**: A floating dashed targeting circle with vertical and horizontal crosshair lines that follows the mouse with smooth elastic lag, reading out real-time coordinate locations (`COORD // X: Y:`).
2. **Magnetic CTA Attractions**: SOUND toggle controls, hamburger bars, and navigation links physically gravitate towards the cursor within a 55px radius.
3. **Matrix Scramble Glitch Text**: Hovering over project cards scrambles the title letters into temporary matrix code characters (`X#%@$`) before resolving them smoothly over 400ms.
4. **Sound Visualizer SVG Waveform**: Three miniature neon cyan vertical bars next to the sound button that bounce dynamically to simulate active synthesizer frequency waves.
5. **Interactive Web-Sling Scroll-to-Top**: A sticky floating web button. Clicking it shoots a vertical web line straight to the ceiling and yanks the scroll focus back to the header using smooth GSAP elastic scrolling.
6. **Spider-Sense Radar Sonar Wave**: Moving the mouse rapidly generates a concentric glowing red ripple expanding outwards from the cursor coordinates.
7. **Scanning Laser Sweep line**: A neon red scanning halftone laser line sweeping from the top to the bottom of the screen continuously.
8. **Flickering Neon Section Header Letters**: Unstable glowing characters in headings that randomly drop their glow intensity and dim, replicating cyber-portal indicators.
9. **CLI Digital Telemetry Console**: A terminal shell in the Contact section that types out secure multidimensional signal telemetry logs in real time.
10. **Vector Corner Brackets Expansion on Hover**: Cards corners slide outwards (`top: -3px; left: -3px;`) and snap from neon blue to electric neon red upon hover.
11. **Virtual Neon Particle Sparks**: Hovering over cards shoots a burst of 15 glowing cyan and red particle sparks spraying outwards from the card center under inertial friction forces.
12. **Concentric Portal opening octagons**: Transitioning between sections triggers a rapid series of 3 concentric glowing SVG web-octagon frames scaling up from the screen center, mimicking a dimensional portal tear.
13. **Staggered 3D Flip comic-panels**: About section panels rotate around a 3D Y-axis (`rotateY(90deg)` to `rotateY(0deg)`) and scale in on scroll viewport entry.
14. **3D Card Icon Parallax Shift**: The SVG graphics within card thumbnails slide in a different ratio (X/Y translation) to the outer card container on mouse-movement, providing layered multi-dimensional depth.
15. **Navbar spider indicator leg twitch**: The navbar indicator spider twitches its legs scurrying dynamically when rapid scroll events are detected.

---

## 🛠️ Local Execution

To run the portfolio locally without any dependencies:

```bash
# Start a simple static web server in the directory
npx http-server -p 8080
```
Open **[http://localhost:8080](http://localhost:8080)** in your browser and perform a hard-refresh (`Ctrl + F5`) to experience next-generation portfolio interaction.
