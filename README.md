# vmPFC Dynamics Analysis Code
This repository contains code and resources pertaining to:

Chang, L.J., Jolly, E., Cheong, J. H., Rapuano, K., Greenstein, N. Chen, PHA, & Manning, J.R. (Under Review). Endogenous variation in ventromedial prefrontal cortex state dynamics during naturalistic viewing reflects affective experience. Preprint bioRxiv. 10.1101/487892

The original preprint is available on [bioRxiv](https://www.biorxiv.org/content/10.1101/487892v1)

# Analysis Code
All code used to perform analyses from the paper are in the Notebook Folder

1. Denoise preprocessed neuroimaging data 
2. Compute Intersubject Correlation Analyses
3. Compute Autocorrelation Analyses
4. Compute All HMM Analyses
5. Compute Facial Expression Analyses
6. Compute Emotion Rating Analyses
7. Compute Inter-experiment Shared Response Model
8. Compute Feature Extraction from FNL Episode 1

# Additional Dependencies
This code requires tools and functions from several other toolboxes developed by our lab including:

- [nltools](https://neurolearn.readthedocs.io/en/latest/): a Python multivariate analysis library available on PyPI

- [fnl_tools](https://github.com/cosanlab/fnl_tools): Helper functions for working with the FNL data available on Github

- [feat](https://github.com/cosanlab/feat): A Python package for performing facial expression analyses and visualization available on Github. 

- [emotionCF](https://github.com/cosanlab/emotionCF): A Python package for performing collaborative filtering available on Github.

- [pymer4](http://eshinjolly.com/pymer4/): A Python wrapper for running Mixed Effects regression models in LMER.

There are likely a number of python packages used across many of the analyses that you will need to have installed including:

- numpy
- scipy
- pandas
- sklearn
- nilearn
- hmmlearn
- matplotlib
- seaborn
- pliers
- nibabel
- wordcloud

# Masks and Brain Maps
Many nifti images related to this project can be found in our [Neurovault collection](https://neurovault.org/collections/9062/) including:
 - The k=50 meta-analytic coactivation parcellation mask 
 - thresholded Group-HMM State Contrast Maps
 - unthresholded Group-HMM State Contrast Maps

# Data Availability
We have tried to make most of the data publicly available.

- Neuroimaging Data will be shared on OpenNeuro
- Study 3 Face Expression Data - Available on [OSF](https://osf.io/f9gyd/). We are only sharing extracted Action Unit Values. We do not have permission to share raw video data.
- Study 4 Emotion Ratings - Available on [OSF](https://osf.io/f9gyd/). Rating data was collected on Amazon Mechanical Turk using a custom Flask [web application](https://github.com/cosanlab/moth_app) built by Nathan Greenstein.


# Acknowledgments
The authors would like to acknowledge Sushmita Sadhuka, Zainab Molani, and Antonia Hoidal who assisted in the data collection. This work was supported by funding from the National Institute of Mental Health R01MH116026 and R56MH080716 and NSF CAREER 1848370 as well as funding from the Young Scholar Fellowship Program by the Ministry of Science and Technology (MOST 109-2636-H-002-006) in Taiwan.
