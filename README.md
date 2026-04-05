<div align="center">

# ⚽ Tactical Command | Pro Match Analytics

*A high-fidelity, interactive tactical board featuring **Dijkstra's Algorithm** and **Cinematic Glassmorphism**.*

[![Status](https://img.shields.io/badge/Status-Operational-064e3b?style=for-the-badge)](#)
[![Tech](https://img.shields.io/badge/Tech-Vanilla_JS-f7df1e?style=for-the-badge)](#)
[![Design](https://img.shields.io/badge/Design-Glassmorphism-3b82f6?style=for-the-badge)](#)

</div>

---

## 📖 Overview

**Tactical Command** is a premium, browser-based visualization engine designed for elite football match analysis. Moving beyond basic drag-and-drop tools, this application merges advanced graph theory with a sophisticated "Emerald Edition" glassmorphism aesthetic.

The experience begins with an immersive **Cinematic Landing Page** featuring 3D perspective animations, leading into a professional tactical workspace. Users can orchestrate complex player movements and utilize **Dijkstra’s Algorithm** to calculate and animate the most efficient passing sequences to the goal in real-time.

---

## ✨ Key Features

* **Cinematic Entry Experience:** Immersive landing page featuring a 3D tactical grid, animated data-stream lines, and chromatic shimmering typography using the **Ultra** and **Playfair** fonts.
* **Premium Glassmorphism UI:** A sleek "SaaS-style" interface built with deep emerald gradients, frosted glass panels, and high-contrast blurred backdrops.
* **Algorithmic Pathfinding:** Powered by **Dijkstra's Shortest Path Algorithm** to find mathematically optimal routes through the defensive line.
* **Interceptive Proximity Logic:** Real-time passing lane analysis that considers distance constraints and player positioning.
* **Dynamic Tactical Roster:** Dual-team sidebar rosters that adapt height to the pitch and provide instant unit selection with refined, low-weight typography for readability.
* **Physics-Based Interaction:** Smooth drag-and-drop mechanics for players with real-time recalculation of trajectories on an HTML5 Canvas overlay.

---

## 🛠️ Technology Stack

* **HTML5:** Semantic architecture with an integrated Canvas rendering layer for tactical lines.
* **CSS3 (Advanced):** * `backdrop-filter` for premium glass effects.
    * `perspective` and `rotateX` for 3D depth on the landing grid.
    * `background-clip: text` for chromatic text shimmer animations.
* **Vanilla JavaScript (ES6+):** Custom graph-theory implementation (Nodes/Edges), Dijkstra logic, and frame-rate optimized ball animations.

---

## 🧠 Algorithmic Core

1.  **Node Generation:** Every player on the pitch is treated as a vertex in a directed graph. The opponent’s goal serves as the terminal node.
2.  **Distance Weighting:** Passing "costs" are calculated using the Euclidean distance formula:  
    $$d = \sqrt{(x_2-x_1)^2 + (y_2-y_1)^2}$$
3.  **Connectivity Constraints:** Edges are only generated if teammates are within a viable passing radius (under 500px) and the passing lane is theoretically open.
4.  **Shortest Path Execution:** The algorithm traverses the graph to find the chain of units that minimizes total travel distance to the scoring zone.

---

<div align="center">

**Developed with precision for Tactical Excellence.** *Designed for coaches, analysts, and developers alike.*

</div>
