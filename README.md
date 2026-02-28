# Tetrahedral Number 3D Visualizer

Welcome to the **Tetrahedral Number 3D Visualizer**, a self-contained, single-file HTML web application that dynamically renders mathematical figurate numbers!

👉 **[Live Preview Available Here](https://jdbsolution.github.io/TetraViz/)**

## What is this app for?

This application allows you to explore and visualize **Tetrahedral Numbers** (3D pyramidal structures) and their relationship to **Triangular Numbers** (2D planar structures).
A tetrahedral number represents a pyramid with a triangular base and three sides, constructed out of individual spheres. The *nth* tetrahedral number is the sum of the first *n* triangular numbers.

**Key Features:**
*   **Interactive 3D Visualization:** Render the base tetrahedral structure up to size `n = 10` using Three.js inside an orbitable workspace.
*   **Layer Inspection Engine:** Using the `k` slider, instantly highlight an isolated *k-th* planar slice, dimming the rest of the 3D model to see exactly how individual triangular numbers stack up to form the overall tetrahedral pyramid.
*   **2D Layer View:** A dynamically animated SVG viewport strictly breaks down the highlighted 3D slice back into its perfect 2D Triangular Number representation. 
*   **Camera Presets:** Examine the structure natively using exact geometric normal viewpoints (`ISO`, `Top`, `Faces`, `Base`).
*   **Export Ready:** In-app features for saving still `.png` screenshots or high-quality `.webm` orbital 360-degree animations directly to your machine. 
*   **Theming:** Quick toggle between Dark and Light rendering modes.

## Acknowledgements 🤖✨
This application was entirely generated and developed alongside **GitHub Copilot** using the **Gemini 3.1 Pro (Preview)** model.

## Running the Project
Since it is a 100% self-contained application, you can simply open the `index.html` file in any modern web browser or run it using a local development server of your choice!
