🚀 Interactive 3D Portfolio | Alex Dev

📖 Description

This project is an interactive web portfolio that merges modern frontend development with 3D modeling. The main goal is to demonstrate the integration of models created in Blender into a web environment using Three.js and WebGL, providing an immersive user experience.

The site simulates a "Gamer/Dev" desktop environment where users can explore, interact with objects, and discover information about my skills and projects.

✨ Key Features

Immersive 3D Scene: A room modeled from scratch in Blender, optimized for the web (GLB format).

Interactivity (Raycasting):

🖱️ Hover: When hovering over objects, floating labels identify them.

👆 Click: Specific interactions like turning the monitor on/off or triggering secret sounds (Try clicking Freddy's nose!).

UI/UX Interface: A modern interface layer built with Tailwind CSS that presents my profile before diving into the 3D experience.

Optimization: Use of compressed textures and clean geometry to ensure smooth performance.

Responsive: Adaptable to different screen sizes.

🛠️ Technologies Used

🎨 3D Modeling & Design

Blender 4.0: For modeling, texturing (UV Mapping), and lighting baking.

Formats: Exported in .glb for maximum web efficiency.

💻 Web Development

HTML5: Semantic structure of the site.

Tailwind CSS: For fast, modern, and responsive user interface styling.

JavaScript (ES6+): Interaction logic and scene control.

🧊 Graphics Engine

Three.js: Main library for rendering the 3D scene in the browser.

GLTFLoader: Model loading.

OrbitControls: Restricted camera control for better UX.

Raycaster: Click detection and interaction system.

📸 Process Gallery
<img width="1598" height="891" alt="freddy" src="https://github.com/user-attachments/assets/4a1612b0-0e58-4485-8515-42dc52ebe384" />

Hard Surface Setup
<img width="1333" height="2000" alt="blender_setup" src="https://github.com/user-attachments/assets/14e12579-06f7-4b84-abb4-e4e989f537e8" />

Organic Modeling
<img width="1333" height="2000" alt="posters" src="https://github.com/user-attachments/assets/cef2f8f8-9343-4055-a8a7-48a9f1a0d1bb" />

UV Texturing







Desktop and peripherals modeling.

Creation of Freddy's plushie.

Custom texture mapping.

🚀 How to Run Locally

If you wish to run this project on your local machine:

Clone the repository:

git clone [https://github.com/gael-88/portafolio.git](https://github.com/gael-88/portafolio.git)


Navigate to the folder:

cd portafolio


Run a local server:
Due to browser security policies (CORS) for loading 3D models, a local server is required.

If using VS Code, install the "Live Server" extension and click "Go Live".

If you have Python installed: python -m http.server

If you have Node.js: npx serve

🎮 Controls

Left Click + Drag: Rotate camera (limited to the center of the room).

Mouse Wheel: Zoom In / Zoom Out.

Click on Screen: Play/Pause video.

Click on Freddy's Poster: ? (Secret).

🔗 Links

Repository: https://github.com/gael-88/portafolio

Instagram: @blueybaass

Developed with 💙 by Alex Dev
