This repository contains a collection of Jupyter notebooks for hands-on atmospheric and climate data analysis using Python. Please report issues, if you find bugs.

# Analysis

### Linear regression
- [regression.ipynb](regression.ipynb): one predictor to one predictand
- [regression_multiple.ipynb](regression_multiple.ipynb): multiple predictors to one predictant
- [regression_multiple_multiple.ipynb](regression_multiple_to_multiple.ipynb): multiple predictors to multiple predictants

### Frequency analysis
- [frequency_analysis.ipynb](frequency_analysis.ipynb): FFT and power spectrum of a sinusoidal signal
- [frequency_analysis_rmm.ipynb](frequency_analysis_rmm.ipynb): FFT, power spectrum, power spectrum density, relationship with variance, power × frequency, and autocorrelation using RMM indices

# Data
- `era5_monthly_sst_5x5.nc`:  ERA5 monthly sea surface temperature (SST) data from ECMWF, interpolated to a 5° × 5° grid. This dataset covers the tropical region (30°S to 30°N) from 1940 to 2023.
- `era5_nino.csv`: Nino indices calculated by [nino_indices.ipynb](nino_indices.ipynb).
- `era5_monthly_t2m_points.csv`: Time series of ERA5 2m temperature data at 5 cities.
- `rmm.csv`: Real-time Multivariate MJO (RMM) Index from BoM.