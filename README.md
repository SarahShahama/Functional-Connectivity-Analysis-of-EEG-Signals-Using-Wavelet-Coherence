# Functional-Connectivity-Analysis-of-EEG-Signals-Using-Wavelet-Coherence
This project performs a functional connectivity analysis of EEG data using wavelet coherence, focusing on alpha-band interactions during resting and motor imagery tasks. 

# Project Overview

EEG provides a powerful window into brain activity, and understanding how different regions communicate is key for insights into neural function. This project applies Morlet wavelet-based coherence analysis to measure frequency-specific synchrony between EEG channels and statistically compares connectivity patterns between resting and motor imagery conditions across subjects.

# Features

Preprocessing of raw EEG data with notch and bandpass filtering, resampling, and detrending.

Extraction of time-frequency information using Morlet wavelet transform.

Computation of alpha-band (8–13 Hz) coherence matrices.

Statistical tests including edge-wise paired t-tests with FDR correction and Network-Based Statistics (NBS) for identifying significant connectivity differences.

Visualization of coherence matrices and brain connectivity graphs.

# Data

Uses the PhysioNet Motor Imagery dataset, working with the first five subjects and runs corresponding to rest and motor imagery.

# How to Run

The project is implemented using Python and relies on libraries such as MNE, NumPy, SciPy, NetworkX, and Matplotlib. See requirements.txt for exact dependencies.

Clone the repository

Install dependencies using pip

Run the main notebook or script to replicate the analysis and visualizations

# Results

Identified wavelet coherence patterns in the alpha frequency band.

Found no statistically significant edges or subnetworks after correction, but observed promising raw effect sizes for some channel pairs.

Established a reusable pipeline for EEG functional connectivity analysis.

# Future Directions

Expand analysis to larger datasets for increased power.

Explore other frequency bands or task conditions.

Apply findings to brain-computer interface or clinical research.

ContactFor questions or collaboration, please contact sarashhama7@gmail.com
