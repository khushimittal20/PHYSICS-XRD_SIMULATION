# X-ray Diffraction (XRD) Simulation

This is a web-based simulation of X-ray diffraction based on Bragg’s Law, built using HTML, CSS, and JavaScript. It includes interactive controls and real-time visualization to help students understand the principles of diffraction in crystals.

## Features

- Adjustable parameters:
  - Theta (θ) angle
  - Lattice constant (a)
  - Wavelength (λ)
  - Interplanar spacing (d)
  - Diffraction order (n)
  - Miller indices (h, k, l)
- Auto-calculation of interplanar spacing from lattice constant and Miller indices
- Bragg's Law validation: `nλ = 2d sinθ`
- Intensity vs 2θ graph using Chart.js
- Interactive ray diagram showing diffraction conditions
- Clean and responsive user interface

## Concepts Covered

- Bragg’s Law
- Crystal structure and lattice planes
- Miller indices and interplanar spacing
- Diffraction intensity and angle dependence

## Technologies Used

- HTML
- CSS
- JavaScript 
- Chart.js (for graph visualization)

## How to Use

1. Clone or download the repository:
   ```bash
   git clone https://github.com/khushimittal20/PHYSICS-XRD_SIMULATION.git
   ```
2. Open index.html in browser.
3. Use the control panel to change parameters. The ray diagram and graph will update in real-time.

## Future Improvements

- Add support for different crystal types (SC, BCC, FCC)
- Material presets (e.g., NaCl, Silicon)
- Option to export data and graphs
- 3D visualization of crystal planes and diffraction

## Contributions

Contributions are welcome and appreciated!

To contribute:

1. **Fork** this repository.
2. **Clone** your fork using.
3. Create new branch:
   ```bash
   git checkout -b feature/your-feature-name
4. Make the changes and commit:
   ```bash
   git commit -m "Add a short description"
5. Push the changes.
6. Open a Pull Request to the main repository with a clear title and description of your changes.
