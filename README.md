# One Thousand Origami Cranes

**Generated by Claude with prompts only, no manual code editing. Took 2 hours.**

---

## Live Demo

Check out the live demo here: [https://rencheng0525.github.io/OneThousandOrigamiCranes/](https://rencheng0525.github.io/OneThousandOrigamiCranes/)

---

## Overview

One Thousand Origami Cranes is an interactive WebGL experience that simulates a flock of origami cranes in 3D space using Three.js. Inspired by the Japanese legend of the Thousand Cranes (千羽鶴), this project showcases elegant flocking behavior and beautiful motion dynamics.

---

## Key Features

1. **Realistic Flocking Simulation**
   - Uses the Boid algorithm to simulate lifelike crane movements.
   - Implements behaviors such as alignment, separation, cohesion, and obstacle avoidance.
   
2. **Traditional Japanese Color Palette**
   - Each crane is assigned a color from an authentic Japanese palette.
   - The aesthetic enhances the visual experience and cultural depth.
   
3. **Interactive Controls (dat.GUI)**
   - Adjust the number of cranes dynamically (1-1000).
   - Toggle between different container environments (**Ball or Box**).
   - Activate the **diffusion effect** to disperse cranes outward.
   - Enable **Time Rewind** to reverse the motion history.
   
4. **WebGL-Powered 3D Rendering**
   - Uses Three.js for smooth, high-performance rendering.
   - Implements fog effects and directional lighting for enhanced depth perception.
   
5. **OBJ Model Loader**
   - Loads and renders a custom origami crane 3D model.
   
6. **Adaptive & Responsive Design**
   - Optimized for different screen sizes and devices.

---

## How to Use

1. **Open the Live Demo**: [One Thousand Origami Cranes](https://rencheng0525.github.io/OneThousandOrigamiCranes/)
2. Use the **dat.GUI panel** to adjust the simulation parameters:
   - Change the number of cranes.
   - Switch between Ball and Box container modes.
   - Experiment with different behavior settings.
3. Click **Time Rewind** to play back the previous motion history.
4. Observe and interact with the mesmerizing crane movements!

---

## Technologies Used

- **Three.js** - WebGL-based 3D rendering.
- **dat.GUI** - Interactive user interface for parameter control.
- **JavaScript (ES6 Modules)** - Core development language.
- **OBJLoader** - To load and render 3D models.
- **HTML & CSS** - Basic structure and styling.

---

## Installation (Local Setup)

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/OneThousandOrigamiCranes.git
   ```
2. Navigate into the project folder:
   ```sh
   cd OneThousandOrigamiCranes
   ```
3. Open `index.html` directly in a browser, or start a local server:
   ```sh
   npx http-server .
   ```
4. Open `http://localhost:8080` in your browser.

---

## Future Enhancements

- **Camera Controls**: Allow users to navigate freely.
- **Custom Textures**: Add variety to crane appearances.
- **Collision Detection**: Improve realism in interactions.
- **WebXR Integration**: Bring the experience into Virtual Reality.

---

## Credits

Developed by **[Your Name]**.

Inspired by the Japanese legend of the **Thousand Origami Cranes (千羽鶴)**, symbolizing hope, peace, and longevity.

---

## License

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute!

