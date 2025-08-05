# Einstein 16π Projection Simulation Suite

This repository contains simulation code supporting the paper:

"Einstein’s Equations as a Real Projection of a Complex Entropy Geometry"  
by Anderson M. Rodriguez (2025)  
[Preprint link forthcoming]

The code demonstrates how classical general relativity curvature can emerge as a projection from a more complete complex entropy geometry. It includes three simulation modules corresponding to the appendices of the paper:

---

## Included Simulations

### 1. Appendix A – Entropy Gradient Visualization
- Demonstrates how imaginary curvature arises from spatial gradients of a phase field \( \theta(x, y) \sim \arctan2(y, x) \).
- Shows the combined complex curvature magnitude before projection.

### 2. Appendix B – Solitonic Field Projection
- Models real and imaginary solitons positioned symmetrically in 2D space.
- Computes and compares their individual and combined gradient structures.
- Visualizes constructive interference as a proxy for projected curvature.

### 3. Appendix C – Entropy-Driven Curvature via Projection
- Defines a complex scalar field \( \Psi(x, \tau) \) with a Gaussian envelope and entropy-modulated phase.
- Projects the field at \( \tau = 0 \) and calculates real, imaginary, and combined curvature estimates.
- Illustrates how classical curvature signatures emerge along entropy-neutral slices.

---

## File Structure

- `einstein_16pi_walkthrough_suite.ipynb`: Jupyter notebook containing all three simulations.
- `figures/`: (optional) Saved visualizations if exported.
- `data/`: (optional) Space for saving simulation output or logs.

---

## Dependencies

- Python 3.x
- `numpy`
- `matplotlib`
- `scipy`

Install with:

```bash
pip install numpy matplotlib scipy
