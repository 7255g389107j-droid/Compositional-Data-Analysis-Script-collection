# ITAGAKI-Research on CoDA
### Absolute Basis Recovery & Geometrical Stability Analysis Framework

A collection of professional R scripts for **Compositional Data Analysis (CoDA)**, focusing on the mathematical reconstruction of absolute mass and the quantification of system entropy. This framework bridges the gap between Aitchison geometry and physical noise models.

## 🔬 Core Methodology
Unlike standard CoDA packages that remain in the "closed" simplex, this system employs the **Triple-Stability Engine** to identify invariant anchors and reconstruct the original absolute basis.

- **V8.0 Chaos Engine:** Quantifies system entropy using Poisson, Aitchison, and Ohta metrics.
- **Itagaki-Elbow System:** Automated optimal anchor selection via variance-gradient analysis.
- **LOO-Stability Tracker:** Leave-One-Out sensitivity analysis to identify system perturbers.

## 🛠 Features
- **Pure Base R Implementation:** Zero dependency on external libraries for maximum reproducibility and long-term stability.
- **Robustness-First Design:** Integrated Bootstrap CI (95%) and MAD-based anomaly detection.
- **Diagnostic-Driven:** Automated "Chaos Index" reporting to prevent the analysis of turbulent/unreliable datasets.

## 📚 Academic Citation
If you use this logic or these scripts in your research, please cite:
1. **Ohta, T. (2011).** *Invariance of Log-Ratios in Compositional Data.* DOI: 10.1007/s11004-011-9332-y
2. **Itagaki, T. (2024).** *The Itagaki-System base.* DOI: 10.3390/microorganisms12071484
3. **Itagaki, T. (2025).** *The Itagaki-System base.* DOI: 10.3390/nu17233681
4. **Itagaki, T. (2026).** *The Itagaki-System: Absolute Basis Deconvolution.* DOI: 10.13140/RG.2.2.21953.93284
5. **Itagaki, T. (2026).** *The Itagaki-System.* DOI: 10.13140/RG.2.2.35015.25762

## ⚖️ License
Licensed under the **MIT License**. 
(c) 2026 Tatsuki Itagaki. All rights reserved.

---
"In a world of proportions, the absolute truth is hidden in the high-quality data."
