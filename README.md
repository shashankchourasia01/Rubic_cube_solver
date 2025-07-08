🧊 Rubik's Cube Solver – Step-by-Step Visual Guide (React)
This project is a Rubik's Cube Solver built using React, designed to guide users step-by-step through solving a standard 3x3 Rubik’s Cube. Users input the cube's current color configuration, and the app intelligently calculates and displays the moves needed to solve it using a simplified solving algorithm.

🎯 Features
✅ Interactive color input for all six faces of the cube (White, Yellow, Green, Blue, Red, Orange)

🧠 Step-by-step solving instructions from start to finish

💡 Color-coded cube face selector (press G for green, R for red, etc.)

🌀 Real-time visual update of cube state

📱 Fully responsive and mobile-friendly design

🛠 Tech Stack
⚛️ React.js (Frontend framework)

🎨 Tailwind CSS / CSS Modules for styling (customizable)

🧩 Cube solving logic implemented using a simplified solving algorithm (e.g., layer-by-layer)

🧱 How It Works
Input the Cube Configuration

Select a color (by key or UI button):

W → White

Y → Yellow

G → Green

B → Blue

R → Red

O → Orange

Click each tile to assign the selected color on all 6 faces (54 tiles in total).

Solve the Cube

After inputting all faces, click "Solve Cube"

The solver will analyze the cube state and generate step-by-step instructions (e.g., F', R, U2, etc.)

Follow Instructions

The app displays each move one-by-one until the cube is completely solved

Optional: 3D or 2D cube visualization (optional enhancement)

🧪 Example Input Format
Each face (9 tiles) is entered with selected color, for example:

mathematica
Copy
Edit
Front (Green face): G G W
                   R G G
                   Y O G
Repeat for all 6 faces before solving.

📦 Installation & Setup
bash
Copy
Edit
git clone https://github.com/your-username/rubiks-cube-solver-react.git
cd rubiks-cube-solver-react
npm install
npm start
The app will run on http://localhost:3000

📁 Project Structure
pgsql
Copy
Edit
rubiks-cube-solver-react/
├── public/
├── src/
│   ├── components/
│   │   ├── CubeFace.js
│   │   ├── ColorPicker.js
│   │   ├── StepSolver.js
│   ├── utils/
│   │   └── solveLogic.js
│   ├── App.js
│   └── index.js
├── package.json
└── README.md
✨ Future Enhancements
🧊 3D Cube View using Three.js

🧠 Advanced solving algorithms like CFOP

📸 Image-based color detection (from webcam)

🗂 Save/Load cube states

🙌 Contributing
Found a bug or want to contribute?
Feel free to open an issue or submit a PR!

📄 License
This project is licensed under the MIT License.

👨‍💻 Author
Shashank Chourasia
MERN Stack Developer
GitHub | LinkedIn | Portfolio

