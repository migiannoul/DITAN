# DITAN (v1.0)
DITAN: Detection and Interpretation of Temporal-based Anomalies

The publication is available on 
Elsevier Pattern Recognition Volume 143, November 2023, 109814
https://www.sciencedirect.com/science/article/abs/pii/S0031320323005125

Abstract:
We present DITAN, a novel unsupervised domain-agnostic framework for detecting and interpreting temporal-based anomalies. 
It is based on an encoder-decoder architecture with both implicit/explicit attention and adjustable layers/units for 
predicting normality as regular patterns in sequential data. A two-stage thresholding methodology with built-in pruning 
is used to detect anomalies, while root cause and similarities are interpreted in data and units space. 
Our approach is designed to intersect the 9 fundamental characteristics extracted from the union of related works. 
We demonstrate the DITAN modules on real-world datasets of 6 multivariate time series contaminated by point and contextual 
temporal-based anomalies at a varying duration. Experiments show a dominant predictability power of DITAN against the
originally proposed models. DITAN is able to determine critical regions and thus identify anomalous events similarly well. 
Informative similarities between anomalous records are interpreted, since almost all similarities in units space are also 
verified in data space.
