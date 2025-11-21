# Computational Mathematics & Python

This directory serves as a computational laboratory for my independent study. The goal is to bridge the gap between abstract theory and computational visualization, implementing algorithms related to Algebraic Topology and Data Analysis.

---

## 1. Current Explorations

### ➡️ [Notebook: TDA Introduction](TDA_introduction.ipynb)
* **Focus:** Computational Topology using the **Gudhi** library.
* **Objective:** To recover the homology groups of a geometric object from a discrete point cloud.
* **Methodology:**
    1.  Generation of a synthetic point cloud sampled from a **Torus ($T^2$)**.
    2.  Construction of **Vietoris-Rips complexes** at varying scales.
    3.  Calculation of Persistent Homology to identify topological features.
    4.  Verification of **Betti Numbers** ($B_0=1, B_1=2$) via Persistence Barcodes.

---

## 2. Technical Stack

The following tools are currently being implemented to support mathematical experimentation:

| Library | Mathematical Application | Utility |
| :--- | :--- | :--- |
| **[Gudhi](https://gudhi.inria.fr/)** | **Algebraic Topology** | Simplicial complexes, Persistent Homology |
| **NumPy** | **Linear Algebra** | Vector spaces, Matrix operations, Data structures |
| **Matplotlib** | **Visualization** | Plotting barcodes and persistence diagrams |

---

### ⬅️ [Return to Main Portfolio](../README.md)
