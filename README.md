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

- HTML5
- CSS3 (Flexbox and Grid)
- JavaScript (ES6+)
- Chart.js (for graph visualization)

## How to Use

1. Clone or download the repository:
   ```bash
   git clone https://github.com/your-username/xrd-simulation.git
   ```
2. Open index.html in browser.
3. Use the control panel to change parameters. The ray diagram and graph will update in real-time.

## Future Improvements

-Add support for different crystal types (SC, BCC, FCC)
-Material presets (e.g., NaCl, Silicon)
-Option to export data and graphs
-3D visualization of crystal planes and diffraction
