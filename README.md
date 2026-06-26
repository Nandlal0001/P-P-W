# 🕸️ Interactive 3D Spider-Verse Portfolio

A highly immersive, interactive personal portfolio website built with **HTML, Tailwind CSS, and Three.js**. This project features a procedurally generated infinite neon cityscape, dynamic cinematic lighting, and a fully integrated 3D Spider-Man character model that reacts to user mouse movements to simulate web-swinging.

## ✨ Features

* **Procedural 3D Cityscape:** Generates an endless scrolling neon city using Three.js native geometries and materials.
* **Interactive Camera Controls:** The camera and 3D character smoothly follow mouse movements, creating a dynamic parallax and "swinging" effect.
* **Cinematic Lighting:** Utilizes Hemisphere, Ambient, Directional, and Neon Point Lights to create a moody, high-contrast visual experience.
* **Warp Speed Navigation:** Clicking on navigation links triggers a hyper-speed 3D visual transition, flying the user through the city to their desired section.
* **Glassmorphism UI:** Responsive, high-contrast floating glass panels built with Tailwind CSS ensure readability over the moving 3D background.
* **External 3D Model Integration:** Uses `GLTFLoader` to render a high-quality `.glb` 3D character asset attached directly to the camera hierarchy.

## 🛠️ Built With

* **HTML5** 
* **Tailwind CSS** (via CDN for rapid UI styling)
* **Vanilla JavaScript** 
* **Three.js** (WebGL 3D Library)
* **GLTFLoader** (For loading `.glb` 3D model assets)

## 🚀 How to Run Locally

Because this project loads an external 3D model file (`.glb`), you **cannot** simply double-click the `index.html` file to view it. Browsers block local files from loading external 3D assets due to CORS security policies. 

You must run this project through a local development server.

### Prerequisites
1. Download and install [Visual Studio Code (VS Code)](https://code.visualstudio.com/).
2. Install the **Live Server** extension by Ritwick Dey in VS Code.
3. Ensure you have the required 3D model file (`spider-man_spider-man_no_way_home.glb`) placed in the exact same root directory as your `index.html`.

### Installation Steps
1. Clone this repository or download the project folder to your machine.
2. Open the project folder in VS Code.
3. Open the `index.html` file.
4. Right-click anywhere in the code editor and select **"Open with Live Server"**.
5. The portfolio will automatically open in your default web browser at `http://127.0.0.1:5500`.

## 📁 Project Structure

```text
├── index.html                                  # Main HTML, UI, and Three.js logic
├── spider-man_spider-man_no_way_home.glb       # External 3D character model
└── README.md                                   # Project documentation

👨‍💻 Author
Nandlal Mahato
First-Year B.Tech Computer Science and Engineering Student
Email: nandlalmahato0001@gmail.com
LinkedIn: Nandlal Mahato

📄 License
This project is open-source and available for educational and portfolio display purposes.
The 3D character asset properties belong to their respective creators and copyright holders.
