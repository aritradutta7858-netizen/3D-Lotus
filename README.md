# 🪷 Luminous Lotus — 3D WebGL Crystal Experience

An interactive 3D crystal blooming lotus experience built with **Three.js** and **WebGL**. Featuring procedural mathematics, radiant starlight tips, organic radial breathing, celestial tree branch growth, and high-fidelity Zen meditation soundscapes.

Created with passion by **Aritra Dutta**.

---

## ✨ Features

- **Procedural Crystal Petals**: Custom Three.js `ShaderMaterial` rendering glass translucency, razor-sharp edge specular highlights, and flowing golden energy waves pulsating along delicate veins.
- **Sacred Geometry Mandala**: 4 sculpted concentric petal layers (36 petals: 6, 8, 10, 12) forming an uncluttered sacred lotus mandala from the top view.
- **Celestial Tree Branch & Stardust Intro**:
  - 8 golden fractal branches and 16 secondary twigs (24 branches total) dynamically growing outward beneath the lotus.
  - 220 stardust motes swirling inward in a cosmic vortex to ignite the central golden core.
  - Expanding celestial shockwave ring dissipating across the void as petals unfurl.
- **Radiant Golden Heart**: Realistic carpellary seed pod with 72 delicate golden stamens swaying organically in 3 tiers.
- **Dual Ambient Soundtracks**:
  - *Zen Meditation*: Authentic Tibetan singing bowls, ceremonial gongs, and temple chimes.
  - *Celestial Ambient*: Gentle ambient synth pads and harmonic piano arpeggios.
  - Silky volume fade-ins and cross-fading.
- **Camera Perspectives**:
  - **Top Mandala**: Symmetrical top-down view.
  - **Cinematic**: The aesthetic perspective inspired by luxury 3D art reels.
  - **Profile**: Side elevation highlighting the curved geometry and stem.
- **Interactive Creator Watermark**:
  - Glassmorphic badge in the bottom corner.
  - Interactive click sends energy shockwaves through the 3D flower, plays an 864Hz celestial chime, and emits floating blossom sparkles.
- **Zero External 3D Dependencies**: 100% procedural geometry and canvas-generated textures — completely self-contained and fast loading.

---

## 🚀 Live Demo & Local Setup

### Option 1: Direct File
Simply double-click or open `index.html` in any modern web browser.

### Option 2: Local HTTP Server
```bash
# Python 3
python3 -m http.server 8000

# Node.js
npx serve .
```
Navigate to `http://localhost:8000/index.html`.

---

## 🌐 Deploy to GitHub Pages

1. In your repository on GitHub, navigate to **Settings** > **Pages**.
2. Under **Build and deployment** > **Source**, select **Deploy from a branch**.
3. Under **Branch**, select `main` and `/ (root)`.
4. Click **Save**. Your site will be live at:
   `https://aritradutta7858-netizen.github.io/3D-Lotus/`

---

## 🛠️ Built With

- [Three.js r128](https://threejs.org/) — 3D WebGL library
- [OrbitControls & EffectComposer](https://threejs.org/docs/#examples/en/controls/OrbitControls) — Smooth camera navigation & Unreal Bloom post-processing
- [Google Fonts](https://fonts.google.com/) — Cinzel & Plus Jakarta Sans
- Vanilla CSS3 — Glassmorphic styling with backdrop-filter

---

## 📄 Credits & License

- **Visuals & Development**: Created by [Aritra Dutta](https://github.com/aritradutta7858-netizen)
- **Audio**:
  - *Ancient Rite* by Kevin MacLeod ([Incompetech](https://incompetech.com)) — Licensed under CC BY 4.0
  - *Placid Ambient* by MusicLFiles — Licensed under CC BY 4.0
- **Code License**: MIT License
