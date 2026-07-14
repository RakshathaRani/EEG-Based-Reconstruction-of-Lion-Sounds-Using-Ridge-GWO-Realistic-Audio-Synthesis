<p align="center">
  <img src="banner.png" alt="EEG Audio Reconstruction Banner" width="100%">
</p>

# 🧠 EEG-Based Reconstruction of Lion Sounds Using Ridge Regression, Grey Wolf Optimization and Griffin-Lim Audio Synthesis

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![PyQt5](https://img.shields.io/badge/PyQt5-GUI-green?style=for-the-badge)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange?style=for-the-badge)
![Signal Processing](https://img.shields.io/badge/Signal-Processing-red?style=for-the-badge)
![EEG](https://img.shields.io/badge/EEG-Analysis-blueviolet?style=for-the-badge)
![Audio Reconstruction](https://img.shields.io/badge/Audio-Reconstruction-success?style=for-the-badge)
![Research Project](https://img.shields.io/badge/MCA-Final%20Year%20Project-darkgreen?style=for-the-badge)

</p>

---

# 📖 About the Project

This repository presents an advanced research project focused on reconstructing realistic lion vocalizations from synthesized EEG signals using modern machine learning and signal processing techniques.

The project combines EEG signal synthesis, feature extraction, Ridge Regression, Grey Wolf Optimization (GWO), and Griffin-Lim audio reconstruction into an integrated framework capable of generating reconstructed lion sounds while providing an interactive desktop dashboard for visualization and analysis.

Unlike conventional audio reconstruction systems, this framework emphasizes optimization-driven signal reconstruction together with detailed visualization of EEG channels, waveform envelopes, reconstruction quality, playback analysis, and performance metrics.

This project was developed as part of my **Master of Computer Applications (MCA) Final Year Research Project**.

---

# 📄 Research Status

### Research Paper

**Title**

> EEG-Based Reconstruction of Realistic Lion Sounds Using Ridge Regression, Grey Wolf Optimization and Griffin-Lim Audio Synthesis

### Publication Status

🟢 **Editor Assigned**

The associated research paper is currently under editorial review.

---

# ⚠️ Source Code Availability

The implementation source code, trained models, datasets, and complete research manuscript are intentionally **not included** in this repository because the associated research paper is currently under editorial review.

This repository has been created solely to showcase:

- Project methodology
- Graphical User Interface (GUI)
- Workflow
- Experimental outputs
- Performance evaluation
- Visual demonstrations

The complete implementation will remain private until the publication process is completed.

---

# ⭐ Project Highlights

✔ EEG Signal Synthesis

✔ Audio Feature Extraction

✔ Ridge Regression Model

✔ Grey Wolf Optimization (GWO)

✔ Griffin-Lim Audio Reconstruction

✔ Interactive PyQt5 Desktop Dashboard

✔ Envelope Comparison

✔ EEG Channel Visualization

✔ Audio Playback Interface

✔ Reconstruction Metrics

✔ Automated Output Generation

✔ Professional GUI

---

# 📚 Table of Contents

- Project Overview
- Objectives
- Research Methodology
- System Workflow
- Features
- GUI Dashboard
- Experimental Results
- Sample Outputs
- Performance Metrics
- Technologies Used
- Repository Structure
- Research Status
- Future Scope
- Disclaimer
- Contact

---

# 🎯 Project Overview

Brain signals contain valuable information regarding auditory perception and neural responses.

The objective of this research is to investigate whether meaningful audio characteristics can be reconstructed using synthesized EEG representations combined with optimization-based machine learning algorithms.

The proposed framework performs the following operations:

- Reads input audio recordings.
- Synthesizes representative EEG signals.
- Extracts envelope-based signal features.
- Applies Ridge Regression for prediction.
- Optimizes reconstruction parameters using Grey Wolf Optimization.
- Reconstructs realistic audio using Griffin-Lim Spectrogram Inversion.
- Displays interactive visualizations using a PyQt5 desktop application.
- Generates reconstructed audio together with detailed evaluation metrics.

The application provides an intuitive graphical interface allowing users to execute the entire reconstruction pipeline with a single click while simultaneously visualizing each processing stage.

---

# 🎯 Objectives

The primary objective of this research is to investigate the feasibility of reconstructing realistic lion vocalizations using synthesized EEG signals combined with optimization-driven machine learning algorithms.

The project specifically aims to:

- Develop an end-to-end EEG-based audio reconstruction framework.
- Simulate EEG signals from input audio recordings.
- Extract meaningful signal features for machine learning.
- Train a Ridge Regression model for audio reconstruction.
- Optimize reconstruction parameters using Grey Wolf Optimization (GWO).
- Reconstruct realistic lion sounds using Griffin-Lim Audio Synthesis.
- Visualize EEG signals, waveform envelopes, and reconstruction performance.
- Provide an interactive desktop application for executing the complete reconstruction pipeline.
- Evaluate reconstruction quality using multiple statistical metrics.

---

# 🔬 Research Methodology

The proposed framework consists of several sequential stages designed to reconstruct audio from synthesized EEG representations.

The methodology combines modern signal processing techniques with optimization-based machine learning.

The major phases include:

### 1️⃣ Audio Acquisition

The system accepts lion vocalization recordings in WAV format.

These recordings serve as the primary input for EEG synthesis and reconstruction.

---

### 2️⃣ EEG Signal Synthesis

Instead of requiring expensive EEG acquisition hardware, representative EEG signals are synthesized from the audio recordings using envelope-guided signal modeling.

The synthesized EEG preserves temporal variations useful for subsequent learning.

---

### 3️⃣ Audio Preprocessing

The audio undergoes preprocessing including:

- Normalization
- Noise handling
- Envelope extraction
- Spectral analysis
- Window segmentation

These preprocessing steps improve reconstruction quality.

---

### 4️⃣ Feature Extraction

Important temporal and statistical features are extracted from synthesized EEG signals including:

- RMS Energy
- Peak-to-Peak Amplitude
- Envelope Characteristics
- Statistical Moments
- Time-domain Features

These features become inputs to the regression model.

---

### 5️⃣ Ridge Regression

Ridge Regression is employed to establish the relationship between synthesized EEG features and audio characteristics.

The model reduces overfitting while improving reconstruction stability.

---

### 6️⃣ Grey Wolf Optimization (GWO)

Grey Wolf Optimization is used to determine the optimal parameters that minimize reconstruction error.

The optimization process searches for the best combination of parameters that maximizes reconstruction quality.

Optimization Parameters include:

- Alpha
- Window Size
- Step Size

---

### 7️⃣ Griffin-Lim Audio Reconstruction

The optimized spectrogram is converted back into a realistic audio waveform using the Griffin-Lim algorithm.

This stage generates the reconstructed lion sound.

---

### 8️⃣ Performance Evaluation

The reconstructed audio is evaluated using several statistical metrics including:

- Mean Squared Error (MSE)
- Pearson Correlation
- Reconstruction Accuracy
- Envelope Similarity
- RMS Energy
- Peak-to-Peak Amplitude
- Skewness
- Kurtosis

---

# ⚙️ System Workflow

The complete workflow of the proposed system is illustrated below.

```
Input Audio
      │
      ▼
Audio Preprocessing
      │
      ▼
Envelope Extraction
      │
      ▼
Synthetic EEG Generation
      │
      ▼
Feature Extraction
      │
      ▼
Ridge Regression Model
      │
      ▼
Grey Wolf Optimization
      │
      ▼
Optimized Features
      │
      ▼
Griffin-Lim Reconstruction
      │
      ▼
Reconstructed Audio
      │
      ▼
Performance Evaluation
      │
      ▼
Interactive Dashboard
```

---

# 🏗️ System Architecture

The architecture integrates multiple computational modules into a unified reconstruction framework.

```
                ┌────────────────────┐
                │   Input Audio (.wav)│
                └──────────┬─────────┘
                           │
                           ▼
              Audio Preprocessing Module
                           │
                           ▼
              Envelope Extraction Module
                           │
                           ▼
             EEG Signal Synthesis Module
                           │
                           ▼
              Feature Extraction Module
                           │
                           ▼
                Ridge Regression Model
                           │
                           ▼
             Grey Wolf Optimization
                           │
                           ▼
           Griffin-Lim Reconstruction
                           │
                           ▼
              Performance Evaluation
                           │
                           ▼
               PyQt5 Desktop Dashboard
```

---

# 🔄 Complete Processing Pipeline

The application performs the following automated operations after clicking the **Run Pipeline** button:

1. Load input audio files.
2. Preprocess audio signals.
3. Generate synthesized EEG.
4. Extract statistical features.
5. Train Ridge Regression model.
6. Optimize parameters using Grey Wolf Optimization.
7. Reconstruct audio signals.
8. Generate waveform comparisons.
9. Display EEG channel visualizations.
10. Compute evaluation metrics.
11. Save reconstructed audio.
12. Export plots and graphical results.
13. Display all outputs within the dashboard.

The entire workflow is executed automatically through the graphical user interface.
