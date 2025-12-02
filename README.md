## 📉 Figure Generation: Gravitational Wave Signatures

This repository includes a standalone Python script designed to reproduce **Figure 1** of the paper *"Gravitational Wave Signatures of Structural Complexity in Radiating Collapse."*

It generates a high-resolution comparison between standard vacuum General Relativity (Schwarzschild) ringdown and a dissipative collapse model driven by the Complexity Factor ($Y_{TF}$).

### Key Features
*   **Publication Ready:** Pre-configured to match **APS (Physical Review)** single-column dimensions ($3.375"$ width).
*   **No LaTeX Required:** Uses internal Matplotlib `stix` fonts (MathJax style) to render LaTeX-quality equations without requiring a local TeX installation.
*   **Physics Visualization:** Analytically models the "Complexity Chirp" (phase drift $\delta \omega$) and thermodynamic damping effects.

### Dependencies
The script requires only standard scientific Python libraries:

```bash
pip install numpy matplotlib
