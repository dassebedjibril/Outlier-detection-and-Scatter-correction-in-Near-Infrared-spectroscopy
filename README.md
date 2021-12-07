# Outlier-detection-and-Scatter-correction-in-Near-Infrared-spectroscopy

It is now possible to use machine learning techniques to achieve the results with the Near Infrared **(NIR)** sensor data due to recent advancements of AI. The scan results are mostly scattered and, contain outliers due to change in the light, working distance and human errors during the scanning. To reduce the scattering and to eliminate the outliers, Multiplicative Scatter Correction **(MSC)** and Standard Normal Variate **(SNV)** have been implemented on near-infrared (NIR) data.

We also applied some filters such as **Gaussian filters** (different orders), **Savitzky Golay filter** (different orders) and Haar **wavelet**  (after implementing). The data has been split in such a way that the first column should be **Y** (analyte) and all others should be **X** (spectrum values) for both `Calibration` and `Validation`.


