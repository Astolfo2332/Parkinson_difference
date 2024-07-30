# Analysis of Brain Data to Distinguish Between Healthy Individuals and Parkinson's Disease Patients Using Electroencephalography (EEG)


The Proyecto_1.ipynb is analysis of Brain Data to Distinguish Between Healthy Individuals and Parkinson's Disease Patients Using Electroencephalography (EEG), using fast Fourier transform, in the range of 13 to 30 Hz for each channel. 

Subsequently, the data were filtered to remove unusual values and ensure that all assumptions required for conducting a t-test were met, including normality, homogeneity of variances, and independence. 

The results indicate that, within the examined frequency range and using the applied methods, there were no significant differences in EEG data between healthy individuals and Parkinson's Disease patients. This suggests that the frequency range of 13 to 30 Hz, along with the employed preprocessing and statistical techniques, may not be sufficient to differentiate between the two groups. 

## Using a welch estimator of power specter density and a coherence coefficient

In the "Project 2" folder, there is a variation of this pipeline that employs a coherence coefficient and a Welch estimator for power spectral density analysis. This variation follows the same methodology as previously described to ensure that statistical assumptions, such as normality, homogeneity of variances, and independence, are met, and includes filtering to remove unusual data.

The results indicate that neither of these additional methods revealed any statistical differences between the groups.