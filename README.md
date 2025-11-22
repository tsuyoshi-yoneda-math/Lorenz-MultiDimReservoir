Please acknowledge the use of these scripts in any publications that make use of them.

As shown in Reservoir3setsScheme_MultiDimLongData.ipynb, <b>Lorenz-63 for the 1000-step-ahead prediction (nondimensional time of 10) achieves a MAE of 0.014</b> for the standardized dataset, computed as the mean error over the entire prediction horizon.


Comparison with Feng et al. (2025)

https://www.frontiersin.org/journals/big-data/articles/10.3389/fdata.2024.1506443/full

Feng et al. (2025) report a non-standardized MAE ≈ 1.19 for the Lorenz-63 system at t = 10 (1000 steps), computed as the mean error over the entire prediction horizon. When converted into the standardized scale, this corresponds to a standardized MAE of <b>approximately 0.10–0.12.</b>

However, their training dataset consists of only 6,000 samples, whereas ours contains 600,000, so this difference should naturally be taken into account.　Even so, under a straightforward comparison, our model clearly outperforms theirs.
