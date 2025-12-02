# 🌊 Max-Flow Hub

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Tech-D3.js-FF6B6B?style=for-the-badge&logo=d3.js">
  <img src="https://img.shields.io/badge/Style-Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">
</p>

<p align="center">
  <strong>Master network flow algorithms through interactive visualization</strong><br>
  <em>See the algorithms. Understand the theory. Build intuition.</em>
</p>

<p align="center">
  <a href="https://flow.parvpatel.me">🚀 Live Demo</a> •
  <a href="#features">✨ Features</a> •
  <a href="#getting-started">🎯 Quick Start</a> •
  <a href="#algorithms">🧠 Algorithms</a>
</p>

---

## 🎯 What is Max-Flow Hub?

Max-Flow Hub is an **interactive educational platform** that transforms abstract network flow concepts into intuitive visual experiences. Whether you're a student learning graph algorithms, an educator teaching computer science, or a developer brushing up on optimization techniques, this tool makes complex maximum flow algorithms accessible and engaging.

### Why Max-Flow Hub?

- **🎨 Visual Learning**: Watch algorithms execute step-by-step with animated transitions
- **🛠️ Interactive**: Build custom graphs, adjust parameters, and experiment in real-time
- **📚 Comprehensive**: Five integrated modules covering theory, practice, and analysis
- **⚡ No Setup**: Pure client-side application—just open and start learning
- **🎓 Educational**: Detailed logs, explanations, and theorem demonstrations

---

## ✨ Features

### 🎪 Five Integrated Learning Modules

#### 1️⃣ **Home Dashboard**
Central hub providing quick access to all visualization tools with elegant navigation.

#### 2️⃣ **Algorithm Visualizer**
The core experience—build graphs and watch algorithms solve them in real-time.

- **Graph Builder**: Click to add nodes and edges with custom capacities
- **Preset Graphs**: Load standard examples instantly
- **Algorithm Selection**: Choose between Edmonds-Karp, Ford-Fulkerson, or Push-Relabel
- **Playback Controls**: Play, pause, step forward/backward through execution
- **Speed Control**: Adjust animation speed to your learning pace
- **Detailed Logging**: Every BFS/DFS traversal, augmentation, and flow update recorded

#### 3️⃣ **Residual Graph Explorer**
Understand the heart of flow algorithms—residual networks.

- Visualize forward edges (remaining capacity)
- See backward edges (flow reversal opportunities)
- Watch residual graph evolve with each augmentation
- Color-coded edges for intuitive understanding

#### 4️⃣ **Max-Flow Min-Cut Theorem**
Interactive proof that max flow equals min cut.

- Build a graph and find its maximum flow
- Visualize the minimum cut automatically
- See cut capacity calculation in real-time
- Understand the fundamental theorem through interaction

#### 5️⃣ **Complexity Analyzer**
Compare algorithm performance with dynamic charts.

- Adjustable graph parameters (vertices, edge density)
- Side-by-side runtime comparison
- Log-scale visualization for clear trends
- Understand when to use each algorithm

---

## 🧠 Algorithms

### Edmonds-Karp (EK)
**BFS-based augmenting paths**

- **Time Complexity**: O(VE²)
- **Best For**: General-purpose, guaranteed polynomial time
- **Visualization**: BFS tree exploration, shortest augmenting paths

### Ford-Fulkerson (FF)
**DFS-based augmenting paths**

- **Time Complexity**: O(E · max_flow) — pseudo-polynomial
- **Best For**: Small max-flow values, simple implementation
- **Visualization**: DFS stack traversal, augmentation sequences

### Push-Relabel (PR)
**Local preflow operations**

- **Time Complexity**: O(V²E) — FIFO variant
- **Best For**: Dense graphs, parallelizable operations
- **Visualization**: Height labels, excess flow, push/relabel steps

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | HTML5, CSS3, JavaScript (ES6+) |
| **Styling** | Tailwind CSS 3.x |
| **Visualization** | D3.js v7 (force simulation, SVG manipulation) |
| **Architecture** | Pure vanilla JS—no build tools required |
| **Deployment** | Static hosting (works anywhere) |

---

## 🚀 Getting Started

### Prerequisites

None! This is a pure client-side application.

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/maxflow-hub.git

# Navigate to the project
cd maxflow-hub

# Open in browser
open index.html
# or simply double-click index.html
```

That's it! No npm install, no build process, no server needed.

### Using the Visualizer

1. **Open the Visualizer** from the home dashboard
2. **Build a graph**:
   - Click "Add Node" to create vertices
   - Click two nodes to create an edge
   - Enter capacity when prompted
3. **Set source and sink** using the dropdowns
4. **Select an algorithm** (EK, FF, or PR)
5. **Click "Run"** and watch the magic happen!
6. Use **playback controls** to step through the execution


---

## 📂 Project Structure

```
maxflow-hub/
│
├── index.html              # Home dashboard & navigation
├── maxflow.html           # Main algorithm visualizer
├── residual.html          # Residual graph explorer
├── theorems.html          # Max-Flow Min-Cut demonstration
├── complexity.html        # Time complexity analyzer
└── README.md             # You are here!
```

---

## 🎓 Educational Use

Max-Flow Hub is designed for:

- **Computer Science Students**: Visual intuition for abstract algorithms
- **Educators**: Interactive teaching aid for graph theory courses
- **Technical Interviewers**: Demonstrate problem-solving approaches
- **Self-Learners**: Hands-on exploration of classic algorithms

### Suggested Learning Path

1. Start with **preset graphs** in the visualizer
2. Run each algorithm and observe differences
3. Explore the **residual graph** to understand capacity networks
4. Prove the **Max-Flow Min-Cut theorem** interactively
5. Compare **complexity** for different graph sizes
6. Build **custom graphs** to test edge cases

---

## 🤝 Contributing

Contributions are welcome! Here are some ideas:

- Add more algorithms (Dinic's, Capacity Scaling)
- Implement graph import/export
- Add more preset graph examples
- Improve mobile responsiveness
- Translate to other languages

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **D3.js Community**: For incredible visualization capabilities
- **Tailwind Labs**: For beautiful, utility-first styling
- **Algorithm Pioneers**: Edmonds, Karp, Ford, Fulkerson, Goldberg, Tarjan
- **Open Source Community**: For inspiration and tools

---

## ⭐ Show Your Support

If Max-Flow Hub helped you understand network flow algorithms:

- **Star** ⭐ this repository
- **Share** with classmates and colleagues
- **Use** in your courses or workshops
- **Contribute** improvements and features

---

<p align="center">
  <strong>Built with ❤️ for algorithm enthusiasts everywhere</strong><br>
  <sub>Making theoretical computer science visual, interactive, and accessible</sub>
</p>

<p align="center">
  <a href="https://flow.parvpatel.me">🌐 Visit Live Demo</a>
</p>
