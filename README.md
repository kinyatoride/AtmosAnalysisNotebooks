This repository contains a collection of Jupyter notebooks for hands-on atmospheric and climate data analysis using Python. Please report issues, if you find bugs.

# Analysis

### Basics
- [linalg_matrix.ipynb](linalg_matrix.ipynb): Basic linear algebra using numpy. Dot product, indentity matrix, inverse maxtrix, determinant, trace, eigenvalues/eigenvectors, Gram matrix

### Linear regression
- [regression.ipynb](regression.ipynb): one predictor to one predictand
- [regression_multiple.ipynb](regression_multiple.ipynb): multiple predictors to one predictant
- [regression_multiple_multiple.ipynb](regression_multiple_to_multiple.ipynb): multiple predictors to multiple predictants

### Frequency analysis
- [frequency_analysis.ipynb](frequency_analysis.ipynb): FFT and power spectrum of a sinusoidal signal
- [frequency_analysis_rmm.ipynb](frequency_analysis_rmm.ipynb): FFT, power spectrum, power spectrum density, relationship with variance, power × frequency, and autocorrelation using RMM index

### EOF
- [EOF_simple.ipynb](EOF_simple.ipynb): EOF analysis using a simple data
- [EOF_sst.ipynb](EOF_sst.ipynb): EOF analysis using 2D SST data containing missing values

### Machine Learning
- [fcnn.ipynb](fcnn.ipynb): Fully connected neural network (FCNN). Forecast Nino 3.4 index using the principal components of SST.

# Data
- `era5_monthly_sst_5x5.nc`:  ERA5 monthly sea surface temperature (SST) data from ECMWF, interpolated to a 5° × 5° grid. This dataset covers the tropical region (30°S to 30°N) from 1940 to 2023.
- `era5_nino.csv`: Nino indices calculated by [nino_indices.ipynb](nino_indices.ipynb).
- `era5_monthly_sst_pc.nc`: Principal components of ERA5 monthly SST calculated by [EOF_sst.ipynb](EOF_sst.ipynb).
- `era5_monthly_t2m_points.csv`: Time series of ERA5 2m temperature data at 5 cities.
- `rmm.csv`: Real-time Multivariate MJO (RMM) Index from BoM.