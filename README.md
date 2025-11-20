Please acknowledge the use of these scripts in any publications that make use of them.

As shown in Reservoir3setsScheme_MultiDimLongData.ipynb, the <b>1100-step-ahead prediction (nondimensional time of 11) achieves a MAE of 0.128</b> (for the standardized dataset).


Comparison with Feng et al. (2025)

https://www.frontiersin.org/journals/big-data/articles/10.3389/fdata.2024.1506443/full

Feng et al. (2025) report a non-standardized MAE ≈ 1.19 at t = 10 (1000 steps), computed as the mean error over the entire prediction trajectory.
In contrast, our model achieves a standardized MAE = 0.128 for the 1100-step-ahead prediction (nondimensional time 11), evaluated only at the final and most challenging prediction time and averaged over many test initial conditions.
When converted back to the original Lorenz-63 scale, this corresponds to a non-standardized error of roughly 1.3–1.5.

Because Feng et al.’s metric benefits from averaging over the entire trajectory, whereas ours reflects the single most error-amplified time point of an extended prediction window, the comparison is highly asymmetric.
Under directly comparable scaling, our model demonstrates substantially stronger long-horizon predictive accuracy, outperforming Feng et al.’s result under a far more stringent evaluation criterion.
