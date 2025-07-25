# MDC Buckling Tool

This repository provides an Excel-based calculator for predicting **knockdown factors (KDF)** of axially compressed cylindrical and conical shells using the **Mechanistic Design Curve (MDC)** introduced in:

> Wagner et al. (2025), *Structured Chaos: Redefining the Design of Buckling-Critical Cylindrical Shells*, Proceedings A.

The tool offers a modern alternative to the conservative NASA SP-8007 method by incorporating probabilistic FEM-based simulations and interpolation over geometric parameters.

---

## Features
- 2D interpolation of KDF based on Batdorf parameter (Z) and relative imperfection amplitude (w/t)
- Fully functional in Excel 365 and Excel 2019
- Visual feedback (✅/❌) on input validity and extrapolation
- Dynamic plots for KDF vs. Z and w/t
- Disclaimer, license terms, and usage guidelines included

📬 For licensing questions or collaboration inquiries, contact:
mdc.buckling@proton.me


The published paper includes the core knockdown factor tables to support academic transparency and reproducibility.  
However, the official Excel implementation includes additional interpolation logic, validation routines, and internal safeguards not covered in the publication.  

🔒 For reliable and consistent results, we strongly recommend using the official tool provided here, rather than attempting to recreate it manually.
