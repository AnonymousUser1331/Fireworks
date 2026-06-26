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

###  Phase 1: The Core Foundation (`fireworks-v1.html`)
* **Overview:** A lightweight 3D projection sandbox built completely from scratch without external libraries.
* **Tech Stack:** Vanilla JavaScript, HTML5 2D Canvas API.
* **Key Implementation:** Uses a manual perspective depth scaling factor to map random spherical particle distributions on a 2D viewport:
  $$\text{Scale} = \frac{\text{Focal Length}}{\text{Focal Length} + z}$$

###  Phase 2: High-Density Cosmic Galaxy Shaders (`fireworks-v2.html`)
* **Overview:** Transitioning heavy computational operations to the GPU to handle massive particle overheads smoothly.
* **Tech Stack:** Three.js, WebGL, Custom GLSL Vertex & Fragment Shaders.
* **Key Implementation:** Features an analytical solution of motion with exponential fluid drag ($1 - e^{-kt}$) to accurately mimic atmospheric air resistance. Includes multi-stage *Crossette* crackle bursts and an incandescent thermal color mapping profile that shifts from a blinding white-hot core to chemical hues, ending in glowing embers.

###  Phase 3: The Interactive Ground Control Engine (`festive-engine-final.html`)
* **Overview:** The final consolidated build, combining cosmic galaxy shell structures with an interactive ground-level firecracker deployment system.
* **Tech Stack:** HTML5 Canvas, Magnetic Text Vector Math, Custom Rotational Vector Matrices.
* **Key Features:**
  * **Magnetic Particle Constellation:** The "Happy Diwali" display is baked out of a scanned image buffer into hundreds of independent glowing nodes. The particles dynamically disperse when interacting with your cursor's proximity push-force field before easing back to their home slots.
  * **Anar (Fountain Pot):** Simulates a high-density, vertical conical vector spray ($V_y \gg V_x$) with active gravitational decay.
  * **Chakri (Ground Spinner):** Tracks a moving angular variable ($\theta$) to eject shimmering sparks tangentially perpendicular to the rotating radial ring boundary ($\theta + \pi/2$).

---

##  Architectural Highlights

* **Additive Blending:** Leverages WebGL's additive blending mode (`THREE.AdditiveBlending`) to smoothly overlay thousands of overlapping light trails, naturally creating hyper-bright, high-intensity explosion centers.
* **GPU Parallelism:** Offloads individual vector updates directly to the graphics card, enabling the simulation of over 8,000 active particles at a smooth 60 FPS.
* **Fluid Trailing Glow:** Uses high-retention alpha clear rect frame wipes rather than instant clearing functions to generate organic, camera-lens style trail burns.

---

##  Installation & Quick Start

Since this framework is engineered entirely using native front-end web standard technologies, it requires no local compilation or dependency installation:

1. **Clone the repository:**
