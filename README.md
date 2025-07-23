# Procedural Planet Generator

This is an interactive web-based application that uses WebGL and procedural generation techniques to create and render unique 3D planets in real-time. Users can customize the planets, choosing from different styles and adjusting various terrain features.

This project was inspired by a prompt from Mysterious_Finish543 on Reddit, which I shamelessly stole.

---

## Features

### 🌐 Real-Time 3D Rendering
- Entirely GPU-accelerated using WebGL (via Three.js) for smooth, interactive performance.
- Now modularized using ES Modules for better scalability and maintainability.

### 🪐 Planet Styles
Choose from a variety of preset planet types, each with unique features and controls:
- **Earth** – Oceans, biomes, polar caps, standard atmosphere.
- **Mars** – Craters, thin CO₂ atmosphere, dust storms.
- **Tatooine** – Twin suns, desert landscape, dry atmosphere.
- **Death Star** – Metallic surface, operational superlaser, equatorial trench.

### 🔁 Procedural Generation
- Every planet is uniquely generated using a random seed.
- Click "Generate New World" for a brand new terrain, cloud system, and environmental data.

### 🧭 Interactive Controls
- **Camera:** Orbit and zoom freely around the planet.
- **Time of Day Slider:** Rotate the sun dynamically for sunrise, noon, or sunset lighting.
- **Terrain Controls:** Contextual sliders for each planet (e.g., ocean level, crater size, trench width).
- **Planet Style Selector:** Instantly switch planet types and re-render on the fly.
- **New:** **Planet Naming Field** to name your custom world.
- **New:** **Save & Load Presets** via localStorage.

### 🌌 Visual Enhancements
- **Volumetric Atmosphere:** Realistic light scattering effects and limb glow.
- **Dynamic Clouds:** Procedural clouds that move and cast shadows.
- **Auroras:** Polar aurora shader effects on magnetically active planets.
- **Volcanoes:** Animated volcanoes with lava flow, eruptions, and smoke plumes.
- **Planetary Rings:** Particle-based rings for gas giants and other suitable styles.

### ☄️ Events & Simulation
- **Asteroid Impact:** Trigger asteroid collisions that spawn either rings or moons.
- **Terraforming Mode:** Modify environmental parameters such as sea level, atmospheric density, and average temperature.
- **Colonization Score:** Dynamic viability score based on planetary conditions.

### 🧪 Planetary Data Panel
- Displays randomly generated or calculated attributes such as:
  - Radius
  - Day length
  - Surface temperature
  - Atmospheric composition
  - Ocean coverage
  - Unique metadata per planet type (e.g., "Superlaser: Operational")

---

## 🛠 How to Run

1. Clone or download this repository.
2. Open the `index.html` file in any modern desktop browser that supports WebGL.

> No build tools or server setup required.

---

## 🔮 Roadmap

- Port to WebGPU (with WebGL fallback)
- Planet export (image or STL)
- Mini solar system view with orbital simulation
- City/civilization overlays for populated planets
- Dynamic weather systems and storm tracking

---

## 📜 License

MIT — because planetary exploration should be free.

---

## 👽 Credit

Original idea and inspiration from [u/Mysterious_Finish543](https://www.reddit.com/user/Mysterious_Finish543) on Reddit.