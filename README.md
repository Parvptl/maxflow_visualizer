🌐 Max-Flow Hub
Interactive Visual Learning Suite for Maximum Flow Algorithms
<p align="center"> <img src="https://img.shields.io/badge/Status-Active-success?style=flat-square"> <img src="https://img.shields.io/badge/Tech-D3.js-blue?style=flat-square"> <img src="https://img.shields.io/badge/Style-TailwindCSS-38bdf8?style=flat-square"> <img src="https://img.shields.io/badge/Algorithms-FF%2C%20EK%2C%20PR-orange?style=flat-square"> <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"> </p> <p align="center"> <b>Visualize. Learn. Interact.</b><br> A complete suite for understanding network flow algorithms through intuitive, interactive visualizations. </p>
🚀 Live Demo

👉 https://flow.parvpatel.me

📸 Screenshots

Replace the placeholders below with actual screenshots.

🔹 Home Dashboard
<p align="center"><img src="screenshots/home.png" width="80%"></p>
🔹 Max-Flow Visualizer
<p align="center"><img src="screenshots/visualizer.png" width="80%"></p>
🔹 Residual Graph Visualizer
<p align="center"><img src="screenshots/residual.png" width="80%"></p>
🔹 Max-Flow Min-Cut Theorem Visualizer
<p align="center"><img src="screenshots/theorem.png" width="80%"></p>
🔹 Time Complexity Comparison
<p align="center"><img src="screenshots/complexity.png" width="80%"></p>
🎯 Overview

Max-Flow Hub is an interactive educational platform that teaches the Maximum Flow problem through rich visualizations, real-time simulations, and detailed algorithm walkthroughs.

It contains five main modules:

Module	Description
Home	Central dashboard linking to all visual tools
Visualizer	Build custom graphs, run algorithms step-by-step
Residual Graph	Understand forward/backward residual capacities
Theorems	Interactive Max-Flow Min-Cut demonstration
Complexity	Dynamic runtime comparison with D3 charts
🧠 Algorithms Included
✔ Edmonds–Karp (EK)

BFS-based augmenting paths

Guaranteed polynomial time

Full step log + path highlighting

✔ Push-Relabel (PR)

Height function

Excess flow

Push / Relabel steps

FIFO variant

✔ Ford–Fulkerson (FF)

DFS-based augmenting paths

Included in visualizer (removed from complexity section)

🛠️ Tech Stack
Layer	Technology
Frontend	HTML5, TailwindCSS, D3.js
Visualization Engine	D3 force-simulation, SVG-based drawing
Algorithm Logic	Pure vanilla JavaScript
UX	Smooth animations, dark mode, playback controls
🔍 Features
🎨 Interactive Graph Builder

Add nodes

Add edges with custom capacity

Set source and sink

Predefined graphs

▶️ Step-by-Step Algorithm Execution

Play / pause

Previous / next step navigation

Speed control

Full log of BFS/DFS/PR events

🔄 Residual Graph Engine

Forward edges (capacity – flow)

Backward edges (flow)

Automatic updates after each augmentation

🧮 Theorem Visualizations

Max-Flow = Min-Cut demonstration

Cut-set highlighting

Real-time curve drawing

📊 Complexity Analyzer

Adjustable V (vertices)

Adjustable density (%)

Log-scale comparison of EK, FF, PR

📁 Project Structure
📦 Max-Flow Hub
│
├── index.html           # Home Dashboard
├── maxflow.html         # Visualizer
├── residual.html        # Residual Graph Demo
├── theorems.html        # Max-Flow Min-Cut Theorem
└── complexity.html      # Time Complexity Comparison

🧪 Local Setup

No installation required.

git clone <your-repo-url>
cd maxflow-hub


Then simply open:

index.html


in any modern browser.
(Chrome recommended for best D3 performance.)

📜 License

This project is licensed under the MIT License.

🙌 Credits

Built as part of the Visulizer Project, designed to make theoretical computer science more intuitive through interactive learning.

⭐ Support the Project

If you found this helpful:

➡️ Star ⭐ the repository
➡️ Share it with classmates
➡️ Use it in your algorithm courses or workshops
