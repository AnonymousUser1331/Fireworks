#  Interactive 3D Fireworks & Festive Light Engine

A high-performance, interactive front-end web application featuring realistic 3D fireworks, custom particle mechanics, and traditional Indian firecrackers. Engineered entirely through the **Vibe Coding** paradigm during **Diwali 2025**, this repository documents the iterative transition from a basic 2D layout to a GPU-accelerated WebGL physics pipeline.

---

##  Development Methodology: Vibe Coding & AI Collaboration

This suite of projects represents a modern shift in software engineering. Instead of manually typing out tedious WebGL boilerplate contexts or flat coordinate arrays, the entire codebase was structurally orchestrated using advanced AI prompting, continuous code auditing, and human-in-the-loop logic debugging.

### Why this is Modern Engineering:
* **Architectural Direction:** The decision to iteratively refactor the codebase—moving from a standard CPU-bound 2D Canvas array to a 3D perspective matrix, and finally to a GPU-accelerated Three.js shader pipeline—was entirely human-directed.
* **Complex Feature Integration:** Blending real-world physics into geometric math models (such as tracking proximity-based magnetic text forces and implementing tangential velocity wrappers for spinning ground elements) required precise logical synchronization.
* **Active Code Review:** Every AI-generated code block was reviewed and refined in real-time, catching and correcting subtle syntax anomalies between high-level JavaScript and low-level GLSL shader data types.

---

##  The Project Evolution (Milestones)

This repository tracks the step-by-step progress of the codebase, demonstrating how the mechanics were optimized for enhanced realism and rendering efficiency.

### 📦 Phase 1: The Core Foundation (`Fireworks`)
* **Overview:** A lightweight 3D projection sandbox mapping coordinate points.
* **Key Feature:** Establishes standard viewport perspective scaling matrices.

### ⚡ Phase 2: WebGL City Skyline & Volumetric Clouds (`Fireworks2`)
* **Overview:** Renders a clean 3D cityscape silhouette against dense, mist-like particle clusters.
* **Key Feature:** Utilizes WebGL contexts to calculate volumetric expansion of deep green and orange particle bursts simultaneously above the horizon line.

### 🎨 Phase 3: High-Performance Trail Tracers (`Fireworks3`)
* **Overview:** A fast canvas build emphasizing crisp light paths and standard typography overlay layout.
* **Key Feature:** Focuses on fluid alpha-wipe trails that make rockets look sharp as they streak up towards a bold festive header.

### 🎛️ Phase 4: Ground Control Dashboard & Particle Constellation (`Fireworks4`)
* **Overview:** The final interactive application featuring multi-mode functionality.
* **Key Features:**
  * **Interactive Selection Menu:** A sleek bottom menu component to seamlessly toggle between Sky Rockets, Anars, and Chakris.
  * **Conical Anar Fountains:** Simulates realistic sparkling golden floor fountains with randomized pressure heights.
  * **Dot-Matrix Grid Text:** The greeting text is rendered as independent glowing particle elements forming an intricate glowing constellation.

---

##  Architectural Highlights

* **Additive Blending:** Leverages WebGL's additive blending mode (`THREE.AdditiveBlending`) to smoothly overlay thousands of overlapping light trails, naturally creating hyper-bright, high-intensity explosion centers.
* **GPU Parallelism:** Offloads individual vector updates directly to the graphics card, enabling the simulation of over 8,000 active particles at a smooth 60 FPS.
* **Fluid Trailing Glow:** Uses high-retention alpha clear rect frame wipes rather than instant clearing functions to generate organic, camera-lens style trail burns.

---

##  Installation & Quick Start

Since this framework is engineered entirely using native front-end web standard technologies, it requires no local compilation or dependency installation:

1. **Clone the repository:**
