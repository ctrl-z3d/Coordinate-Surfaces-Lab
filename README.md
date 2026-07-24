# Coordinate Surface Lab
> **Interactive 3D visualization of coordinate surfaces built with Three.js for EEE241 · Electromagnetic Waves and Fields.**

## Overview
Coordinate Surface Lab is a browser-based educational tool that transforms mathematical coordinate systems into interactive 3D visualizations. It enables students to explore and understand constant-coordinate surfaces in **Cartesian**, **Cylindrical**, and **Spherical** coordinate systems through real-time rendering.

Developed as a learning aid for **EEE241 · Electromagnetic Waves and Fields**.

---

## Preview
<p align="center">
  <img src="./pictures/cartesian%20demo.png" width="48%" alt="Cartesian Coordinate System">
  <img src="./pictures/cyl%20demo.png" width="48%" alt="Cylindrical Coordinate System">
</p>
<p align="center">
  <img src="./pictures/spherical%20demo.png" width="60%" alt="Spherical Coordinate System">
</p>

---

## Features
- Interactive 3D coordinate visualization
- Real-time rendering with Three.js
- Cartesian, Cylindrical, and Spherical coordinate systems
- Constant-coordinate surfaces, intersections, and fill/volume rendering
- Custom equation mode with a math keyboard and adjustable free-variable ranges
- Live HUD readout of current coordinate values and rendered equations
- Live Area / Volume metrics panel with matching closed-form formulas
- Orbit controls for intuitive navigation
- Educational tool for Electromagnetic Waves and Fields

---

## Built With
- Three.js
- HTML5
- JavaScript (ES6)
- CSS3

---

## Getting Started
```bash
git clone https://github.com/ctrl-z3d/Coordinate-Surfaces-Lab.git
cd Coordinate-Surfaces-Lab
```

Run a local web server:
```bash
python -m http.server
```
or
```bash
npx serve
```

Then open:
```
http://localhost:8000/v2_01.html
```

---

## Educational Purpose
This project was developed for **EEE241 · Electromagnetic Waves and Fields** to help students visualize orthogonal coordinate systems used throughout electromagnetics, making abstract mathematical concepts easier to understand through interactive 3D exploration.

---

## Repository Structure
```
Coordinate-Surface-Lab/
│
├── pictures/
│   ├── cartesian demo.png
│   ├── cyl demo.png
│   └── spherical demo.png
│
├── v2_01.html
├── README.md
└── LICENSE
```

---

## Author
**Rakin**
GitHub: https://github.com/ctrl-z3d

---

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
