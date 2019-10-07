# Data-Mining
Meal Detection

# Feature Extraction of CGM data
Features of variation in glucose data for a subject's lunch data over a period of certain days is determined and fed into PCA to get top 5 features.

# Tools Used:
* MATLAB R2019b

# Matlab functions for feature calculations:
* std
* mean
* polyfit
* max
* fillmissing
* isnan
* pca
* zscore

# Features 
1. Distance Vector
2. Coefficient of variation
3. Polynomial coefficients of the graph
4. Time for maximum excursion.


# Distance Vector
* Window size: 3
* feature vector: Distance(window(1)) + Distance(window(2)) +.....+ Distance(window(n))
* 
