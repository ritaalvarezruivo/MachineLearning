## Pulsar Clasification: 
This dataset (HRTU2: https://figshare.com/articles/dataset/HTRU2/3080389) aims to classify neutron stars as Pulsars based on telescope radio signals. Pulsar stars exhibit rapid rotation, emitting a characteristic radio signal that repeats periodically. This distinct radio frequency pattern is detected and labeled as a potential pulsar candidate. However, the majority of these patterns are often obscured by RFI (Radio Frequency Interference) and noise, complicating the identification of true Pulsar stars.

In this dataset, each candidate is characterized by eight continuous variables derived from averaging multiple rotations, determined by the duration of observation. The first four are simple statistics obtained from the integrated pulse profile (folded profile). This is an array of continuous variables that describe a longitude-resolved version of the signal that has been averaged in both time and frequency. The remaining four variables are similarly obtained from the DM-SNR curve. The objective is to automatically assign labels to pulsar candidates, streamlining the analysis process.


1. Mean of the integrated profile.
2. Standard deviation of the integrated profile.
3. Excess kurtosis of the integrated profile.
4. Skewness of the integrated profile.
5. Mean of the DM-SNR curve.
6. Standard deviation of the DM-SNR curve.
7. Excess kurtosis of the DM-SNR curve.
8. Skewness of the DM-SNR curve.
9. Class
   
---

## Clasification Strategy:
1. Data Profiling
2. Data Preparation
3. Feature Selection
4. Classification
5. Best Model Determination

