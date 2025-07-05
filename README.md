# Lattice Boltzmann Solver with Onsager Regularization

This repository presents a cutting-edge **Lattice Boltzmann Method (LBM)** solver designed to handle high Reynolds number incompressible flows with enhanced stability and accuracy. At its core, the solver implements **Onsager regularizers**, leveraging thermodynamically consistent formulations to control numerical instabilities typical in standard LBM at high Re.

> ⚠️ This repository is **not a general-purpose code base**, but a dedicated platform to collect **simulation results and theoretical implementations** related to private sources. More information are intentionally withheld for privacy and intellectual safety concerns.

The project originated in the context of **vortex ring simulations** and has since grown into a versatile tool capable of handling **heavy 3D simulations** for a variety of complex domains. It is built to facilitate exploratory applications of new **collisional models**, with a clear path toward simulations in embedded and irregular geometries.

---

## 🚀 Features

- 🌀 **Onsager Regularizers** for controlled, stable evolution at high Reynolds numbers.
- 📦 Modular structure to easily adapt to new boundary conditions or force models.
- 💻 Ready for **3D simulation** workloads with optimized performance.
- ⚙️ **Highly parallelized CPU performance**, efficient across structured and embedded geometries, thanks to complete PETSc implementation.
- 🧠 Backed by **formal thermodynamic theory** for structure-preserving discretization.
- 📊 Designed as a results-first repository — emphasizing reproducibility and extensibility.

---

## 🧪 Example Output

For example, here you can see the **lid-driven cavity flow at Re = 1000**, simulated with the Onsager-regularized LBM:

![lid_driven_Re_1000.gif](link_to_image_or_gif_if_applicable)

This is one of the canonical benchmarks showing the solver’s ability to remain stable and accurate even at moderately high Reynolds numbers — a challenge for classical LBM without enhancements.

---

## 📁 Structure and Usage

This repo is **under active construction** and will be **heavily expanded over time**.

---

## 🔒 Access and Licensing

This code is primarily intended for private use and internal testing. While scientific principles are openly referenced, the detailed implementations follow protected work from ongoing research and are not intended for broad redistribution at this stage.

---

## 👨‍🔬 Authors

Developed and maintained by **Davide Galbiati**, with inspiration from theoretical advances in thermodynamically consistent numerical schemes and non-equilibrium statistical physics.

---

*This repository is a research-driven effort and serves as a testbed for validating innovative ideas in computational fluid dynamics. Stay tuned for updates and new results!*
