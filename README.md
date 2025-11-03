# Biomedical Data Processing – MATLAB Exercises

## Overview
This repository contains all the exercises developed during the *Biomedical Data Processing* course.  
The purpose of this collection is to apply digital signal processing concepts to real and simulated biomedical data.  
Each exercise focuses on a specific technique used to analyze, filter, and interpret physiological signals such as ECG, EMG, and EEG.

The course progressively introduces fundamental and advanced tools in signal processing:
- signal generation and visualization  
- noise analysis and removal  
- spectral estimation (periodogram, Welch, AR models)  
- correlation and averaging  
- time-frequency analysis (STFT, wavelets)  
- biomedical applications such as ECG filtering, EEG band extraction, and heart rate variability.

All scripts are written in MATLAB Live Script (`.mlx`) format to provide code, output, and explanations in one document.

---

## Exercises Summary

### `es1_sine_signal.mlx`
Generation of a clean and noisy sine signal to study the relationship between amplitude, frequency, duration, and sampling rate.  
Purpose: introduce discrete-time signal representation and noise modeling.

---

### `es2_signal_generation.mlx`
Signal creation using user-defined parameters and Gaussian noise visualization.  
Purpose: explore sampling theory, random noise, and waveform synthesis.

---

### `es3_correlated_average.mlx`
Averaging time-locked segments of a signal to enhance evoked responses.  
Purpose: demonstrate how ensemble averaging improves the signal-to-noise ratio in event-related biomedical signals.

---

### `es4_ecg_artifacts_generation.mlx`
Simulation of common ECG artifacts such as baseline wander, motion noise, and power-line interference, followed by filtering techniques.  
Purpose: understand artifact sources and apply practical filtering to obtain a clean ECG.

---

### `es4_emg_artifacts_generation.mlx`
Addition of artifacts to an EMG-like signal and use of filtering methods to remove interference.  
Purpose: practice interference removal while preserving wideband EMG components.

---

### `es5_filters.mlx`
Implementation of IIR Butterworth filters to remove baseline wander and power-line noise from ECG recordings.  
Purpose: understand filter design, frequency response, and baseline correction.

---

### `es6_indirect.mlx`
Autocorrelation computation of sinusoidal signals to observe periodicity and connections to spectral properties.  
Purpose: introduce the link between correlation and spectral content.

---

### `es6b_eeg_bands.mlx`
Extraction of classical EEG frequency bands (delta, theta, alpha, beta, gamma) using bandpass filters.  
Purpose: learn practical frequency band isolation and visualization.

---

### `es7_periodogram.mlx`
Computation of the periodogram to estimate the power spectral density (PSD).  
Purpose: explore how window type and length affect frequency resolution and leakage.

---

### `es7_welch.mlx`
Power spectral density estimation using Welch’s method with segment averaging.  
Purpose: reduce variance in spectral estimation and compare results with the basic periodogram.

---

### `es8_AR.mlx`
Autoregressive (AR) spectral estimation using a general AR model.  
Purpose: study model-based spectral estimation and resolution improvements on short signals.

---

### `es8_Burg.mlx`
AR spectral estimation with the Burg method, ensuring model stability and better resolution.  
Purpose: compare Burg to other AR methods and observe differences in peak sharpness and variance.

---

### `es8_Yule Walker.mlx`
AR spectral estimation using the Yule–Walker equations.  
Purpose: learn an alternative AR fitting approach and compare its results with Burg and standard AR models.

---

### `es9_tachogram.mlx`
Construction of a heart rate variability (HRV) tachogram and computation of time and frequency domain HRV indices.  
Purpose: analyze cardiac autonomic activity through RR interval variability.

---

### `es10_STFT.mlx`
Short-Time Fourier Transform (STFT) and spectrogram visualization of nonstationary signals.  
Purpose: understand time-frequency trade-offs and observe transient events in biomedical signals.

---

### `es11_Wavelet.mlx`
Wavelet transform for multi-scale time-frequency analysis and signal denoising.  
Purpose: apply wavelet methods to identify transient or nonstationary patterns in physiological signals.

---

## Learning Outcomes
By completing these exercises, the following skills were developed:
- Proficiency in MATLAB for biomedical signal processing.  
- Understanding of frequency-domain and time-frequency analysis methods.  
- Ability to filter and clean physiological signals while preserving diagnostic features.  
- Familiarity with spectral estimation, autocorrelation, and model-based approaches.  
- Application of DSP concepts to real biomedical data such as ECG, EMG, and EEG.

---

## Repository Content
- MATLAB Live Scripts (`.mlx`) for each exercise  
- `README.md` – this file describing the project  
- `LICENSE` – MIT License  

---

## License
Released under the MIT License – free to use, modify, and distribute with attribution.
