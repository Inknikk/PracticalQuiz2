# PracticalQuiz2
Modelling the Solar system using a-frames.
This project is an interactive, web-based 3D visualization of the solar system built with A-Frame. It features a central Sun and nine planets—including Pluto—each textured with high-resolution maps and programmed to revolve at independent speeds to simulate a dynamic orbital environment.

Key Features
Dynamic Orbits: Each planet uses a nested entity structure for smooth, independent revolution.

Asset Management: High-fidelity textures are pre-loaded via the A-Frame asset system.

VR Ready: The scene is built for standard browsers but is compatible with VR headsets.

Because the project loads external textures and scripts, it must be viewed through a local web server (such as VS Code's Live Server or Python’s http.server) to avoid browser CORS restrictions.

Project Structure
The project follows a specific hierarchy to ensure all assets link correctly:

/script: Contains aframe.min.js.

/texture: Contains all planetary and starfield image maps.

index.html: The main scene and animation logic.
