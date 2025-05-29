# Curvality Bayesian Residual Analysis

This repository contains the full pipeline for testing the Curvality theory against CMB residual data using a Bayesian approach. It includes:

- A Colab-compatible Python notebook (`Curvality_Bayesian_Analysis.ipynb`)
- Required dataset (`Residuals_with_Oscillation_Fit.csv`)
- Output traceplot and posterior summaries
- A README for reproducibility

---

## 🔬 Description
The Bayesian model fits a damped sinusoidal structure to the residuals in the EE and TE power spectra, using priors informed by predictions from the Curvality framework. It includes:

- Amplitude prior centered at 1e-12 µK²
- Phase prior centered at 0
- Frequency prior matching oscillatory structure
- Damping scale prior matching visual decay

The model is implemented using PyMC v4 with the numpyro backend.

---

## 📁 Files
- `Curvality_Bayesian_Analysis.ipynb`: Main notebook to run the analysis
- `Residuals_with_Oscillation_Fit.csv`: Residual dataset (ℓ, residuals, fit)
- `trace_plot.png`: Posterior trace visualization
- `posterior_summary.csv`: Exported summary of sampled parameters

---

## 🚀 How to Run
1. Open `Curvality_Bayesian_Analysis.ipynb` in Google Colab
2. Upload `Residuals_with_Oscillation_Fit.csv` when prompted
3. Run all cells to view posterior plots and get the final model summary

---

## 🔗 Citation & Attribution
If you use this notebook, please cite:
> Brett, J. (2025). *Curvality: A Threshold-Based Unified Framework of Gravity, Entropy, and Quantum Decoherence*. (In prep.)

---

## 📬 Contact
For questions, replications, or critiques, open an issue or reach out via [GitHub](https://github.com).
