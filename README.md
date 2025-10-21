
# Logistic Curve Fitting and Visualization in R

This project provides an R script for fitting and analyzing logistic growth curves using both base R and `ggplot2` visualizations. The script includes sections for simulating data, fitting models, comparing fits, plotting residuals, and visualizing parameter effects.

***

### Features

- Simulates and plots logistic-like data.
- Fits logistic models using non-linear least squares (`nls`).
- Compares fits using different starting parameters.
- Visualizes fitted curves, residuals, and parameter effects.
- Provides a `ggplot2`-based visualization of the fit (optional section).
- Contains code to study the impact of individual parameters (`L`, `k`, `x0`).

***

### Requirements

- R (tested with R 4.x or later)
- Packages: `ggplot2`

To install the required package, run:
```r
install.packages("ggplot2")
```

***

### Usage

1. **Run the Script:**
   - Execute in RStudio or with `Rscript logistic-curve.R`.

2. **Main Steps:**
   - **Data Simulation**: Generates noisy logistic data and plots it.
   - **Model Fitting**: Fits logistic models using `nls`.
   - **Plotting**: Visualizes raw data, model fits, and residuals.
   - **Model Comparison**: Compares different initial parameter values for the logistic model.
   - **Parameter Interpretation**: Outputs meaning and estimates for L, k, x0.
   - **ggplot2 Visualization** (*optional*): Plots model fit using `ggplot2` for enhanced aesthetics.
   - **Parameter Effects**: Shows how changes in each parameter affect the logistic curve.

***

### Output

The script produces the following outputs in sequence:

- Scatterplots of simulated data and fitted logistic model
- Overlay plots comparing model fits
- Residual plots
- Estimated parameters and their interpretation
- `ggplot2` visualization (if uncommented)
- Plots illustrating the effect of varying `L`, `k`, and `x0` on the curve

***

### Customization

- Adjust simulation parameters (sample size, noise) in the beginning block as needed.
- Modify starting values for the logistic model to explore convergence and fit differences.
- Enable or disable the `ggplot2` section (uncomment to use).



***





For any questions or contributions, please open an issue or submit a pull request.

[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/84507209/6df55f61-10ab-4035-8e6b-5bed2f8269d9/prac-3-logistic-curve.R)
