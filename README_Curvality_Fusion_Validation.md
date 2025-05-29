# Curvality Fusion Validation

This repository provides a fully reproducible framework for testing the Curvality collapse-driven model of nuclear fusion against real experimental data. It challenges the conventional quantum tunneling mechanism by proposing that entropy and curvature modulate nuclear transitions via deterministic field collapse, derived from a unified Lagrangian framework.

## 🔬 Key Features

- Unified field-theoretic derivation of fusion probability from the Curvality Lagrangian
- Real D–T fusion cross-section data included
- Bayesian model fitting using PyMC
- Comparison against standard quantum tunneling probabilities
- Reproducible notebook with downloadable posterior samples and plots

## 📁 Contents

- `Curvality_Fusion_Validation.ipynb`: Jupyter notebook for Colab or local execution
- `DT_Fusion_Cross_Section.csv`: Cross-section data (D-T reaction)
- `curvality_fusion_fit.png`: Fitted plot comparing Curvality model vs. experimental data
- `Curvality_Fusion_Trace.pkl`: Posterior MCMC samples
- `README.md`: This file

## 📜 Theoretical Background

Fusion probability is redefined using entropy (S), curvature (R), and a collapse field χ:

```
L = 1/2 (∂_μϕ)^2 - 1/2 m²ϕ² - λ/4 ϕ⁴ + αRϕ + βSϕ - χ/6 f(R, S)
```

Leading to a modified fusion probability:
```
P_fusion^Curvality(E, R, S) = η(χ, R, S) · (1 - exp(−E / T_c))
```

## 📎 License

MIT License — feel free to use and cite with attribution.

## 📘 Citation (if DOI added via Zenodo)

> Brett, J. (2025). *Curvality Fusion Validation: Collapse-Driven Field Transitions in Stellar Fusion*. Zenodo. https://doi.org/xx.xxxx/zenodo.xxxxxx

---

For questions or collaboration, please open an issue or contact via GitHub.