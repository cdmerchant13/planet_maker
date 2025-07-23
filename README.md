# Procedural Planet Generator

This is an interactive web-based application that uses WebGL and procedural generation techniques to create and render unique 3D planets in real-time. Users can customize the planets, choosing from different styles and adjusting various terrain features.

This project was inspired by a prompt from Mysterious_Finish543 on Reddit, which I shamelessly stole.

## Features

- **Real-time 3D Rendering:** The entire planet, atmosphere, and effects are rendered on the GPU using WebGL (via three.js), ensuring a smooth, interactive experience.
- **Multiple Planet Styles:** Choose from a variety of planet types, each with its own unique characteristics:
    - **Earth:** A vibrant world with deep oceans, continents, mountains, and polar ice caps.
    - **Mars:** A red, dusty planet with craters and a thin atmosphere.
    - **Tatooine:** A desert world with vast sand dunes and rocky outcrops.
    - **Death Star:** The iconic battle station from Star Wars, complete with a superlaser dish and equatorial trench.
- **Procedural Generation:** Every planet is unique. A "Generate New World" button allows for the creation of a new planet with a random seed.
- **Interactive Controls:**
    - **Camera:** Orbit and zoom the camera to view the planet from any angle.
    - **Time of Day:** A slider to control the position of the sun, which realistically affects the lighting and atmospheric colors.
    - **Terrain:** Each planet style has its own set of controls to modify the terrain, such as ocean level, mountain height, crater size, and more.
- **Volumetric Atmosphere:** A realistic atmosphere with light scattering effects, creating blue skies and red sunsets.
- **Dynamic Clouds:** A procedural cloud layer that casts soft shadows on the surface below (for Earth-like planets).
- **Asteroid Impact:** A button to summon an asteroid that will strike the planet and form either a ring system or a moon.

## How to Run

1.  Clone or download this repository.
2.  Open the `index.html` file in a modern web browser that supports WebGL.

That's it! No server or dependencies are required.
