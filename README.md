<p align="center">
  <img src="banner.png" alt="EEG Audio Reconstruction Banner" width="100%">
</p>

# 🧠 EEG-Based Reconstruction of Lion Sounds Using Ridge Regression, Grey Wolf Optimization and Griffin-Lim Audio Synthesis

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![PyQt5](https://img.shields.io/badge/PyQt5-GUI-green?logo=qt)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![Signal Processing](https://img.shields.io/badge/Signal-Processing-red)
![EEG Analysis](https://img.shields.io/badge/EEG-Analysis-purple)
![Audio Reconstruction](https://img.shields.io/badge/Audio-Reconstruction-success)
![Research Project](https://img.shields.io/badge/MCA-Final%20Year%20Research-blueviolet)

</p>

---

## 📖 About the Project

This repository presents my **Master of Computer Applications (MCA) Final Year Research Project**, which investigates the reconstruction of lion vocalizations from synthesized EEG signals using machine learning, optimization algorithms, and digital signal processing.

The framework combines:

- EEG Signal Synthesis
- Audio Feature Extraction
- Ridge Regression
- Grey Wolf Optimization (GWO)
- Griffin-Lim Audio Reconstruction
- Interactive PyQt5 Desktop Dashboard

The system provides an end-to-end research workflow that reconstructs audio while visualizing EEG channels, waveform envelopes, reconstruction quality, playback analysis, and performance metrics through an interactive graphical interface.

Unlike conventional EEG applications that focus primarily on signal classification, this work explores an optimization-driven framework for reconstructing meaningful audio representations from synthesized EEG signals.

---

> **Notice**
>
> This repository showcases the research methodology, graphical user interface, workflow, and experimental results.
>
> The complete source code, datasets, trained models, project report, and research manuscript are intentionally **not included** because the associated research paper is currently under editorial review.

---

# 📄 Research Status

| Item | Status |
|------|--------|
| Research Project | ✅ Completed |
| Research Paper | 🟢 Under Editorial Review |
| Source Code | 🔒 Private |
| Research Report | 🔒 Private |
| Dataset | 🔒 Private |

---

# ⭐ Project Highlights

- ✅ EEG Signal Synthesis
- ✅ Audio Preprocessing
- ✅ Envelope Feature Extraction
- ✅ Ridge Regression Model
- ✅ Grey Wolf Optimization (GWO)
- ✅ Griffin-Lim Audio Reconstruction
- ✅ Interactive PyQt5 Desktop Dashboard
- ✅ EEG Channel Visualization
- ✅ Envelope Comparison
- ✅ Audio Playback Interface
- ✅ Performance Evaluation
- ✅ Automatic Output Generation
- ✅ Scientific Visualization

---

# 📚 Table of Contents

- [📖 About the Project](#-about-the-project)
- [🎯 Project Overview](#-project-overview)
- [🎯 Objectives](#-objectives)
- [💡 Why This Research?](#-why-this-research)
- [🔬 Research Methodology](#-research-methodology)
- [⚙️ System Workflow](#️-system-workflow)
- [🏗️ System Architecture](#️-system-architecture)
- [🔄 Complete Processing Pipeline](#-complete-processing-pipeline)
- [✨ Features](#-features)
- [🖥️ Interactive Desktop Dashboard](#️-interactive-desktop-dashboard)
- [🎵 Sample Outputs](#-sample-outputs)
- [📊 Performance Metrics](#-performance-metrics)
- [🧪 Technologies Used](#-technologies-used)
- [📁 Repository Structure](#-repository-structure)
- [🎯 Research Contributions](#-research-contributions)
- [💡 Applications](#-applications)
- [🚀 Future Scope](#-future-scope)
- [🎓 Academic Information](#-academic-information)
- [📑 Research Publication](#-research-publication)
- [🏆 Skills Demonstrated](#-skills-demonstrated)
- [🙏 Acknowledgements](#-acknowledgements)
- [📬 Contact](#-contact)

---

# 🎯 Project Overview

Electroencephalography (EEG) is widely used for studying brain activity, neurological disorders, and Brain-Computer Interface (BCI) systems. While most existing research focuses on EEG signal classification or decoding, this project explores a different research direction by investigating whether meaningful audio signals can be reconstructed from synthesized EEG representations.

This project proposes a complete end-to-end framework that integrates signal processing, machine learning, optimization algorithms, and audio synthesis into a unified reconstruction pipeline.

The proposed framework performs the following operations:

- Accepts lion vocalization recordings as input
- Generates synthesized EEG signals
- Extracts informative temporal and statistical features
- Learns feature relationships using Ridge Regression
- Optimizes reconstruction parameters using Grey Wolf Optimization (GWO)
- Reconstructs audio using the Griffin-Lim algorithm
- Evaluates reconstruction quality using multiple statistical metrics
- Presents all results through an interactive PyQt5 desktop application

The project demonstrates how optimization-driven machine learning techniques can be combined with EEG-inspired representations to reconstruct meaningful audio while providing an intuitive research interface for experimentation and visualization.

---

# 🎯 Objectives

The primary objective of this research is to investigate the feasibility of reconstructing lion vocalizations using synthesized EEG signals combined with machine learning and optimization techniques.

Specific objectives include:

- Develop a complete EEG-based audio reconstruction framework
- Generate representative EEG signals from audio recordings
- Extract meaningful signal features for machine learning
- Train a Ridge Regression model for signal reconstruction
- Optimize reconstruction parameters using Grey Wolf Optimization (GWO)
- Reconstruct realistic audio using the Griffin-Lim algorithm
- Visualize EEG signals and reconstruction results through a graphical interface
- Evaluate reconstruction quality using statistical performance metrics
- Provide an interactive desktop application for executing the complete pipeline

---

# 💡 Why This Research?

Traditional EEG research primarily focuses on tasks such as signal classification, mental state recognition, emotion analysis, and Brain-Computer Interface (BCI) applications.

This research investigates a novel direction by exploring whether synthesized EEG representations can be utilized to reconstruct meaningful animal vocalizations.

The proposed framework combines machine learning, optimization algorithms, digital signal processing, and scientific visualization into a unified workflow capable of generating reconstructed lion sounds while providing comprehensive analytical insights.

Rather than functioning as a conventional software application, this project serves as an experimental research platform that demonstrates the integration of Artificial Intelligence, Machine Learning, Signal Processing, and Brain-Computer Interface concepts in a single interactive system.

---

# 🔬 Research Methodology

The proposed framework consists of multiple interconnected stages that transform an input lion vocalization into a reconstructed audio signal through synthesized EEG representations and optimization-driven machine learning techniques.

The methodology integrates signal processing, statistical feature extraction, optimization algorithms, and scientific visualization into a single end-to-end pipeline.

---

## 1️⃣ Audio Acquisition

The reconstruction process begins with a lion vocalization recorded in WAV format.

The selected audio acts as the primary source from which representative EEG signals are synthesized.

---

## 2️⃣ Audio Preprocessing

Before reconstruction, the audio undergoes several preprocessing operations to improve signal quality.

These include:

- Audio Normalization
- Noise Reduction
- Window Segmentation
- Envelope Extraction
- Spectral Analysis

Preprocessing ensures stable feature extraction and improved reconstruction quality.

---

## 3️⃣ EEG Signal Synthesis

Instead of relying on expensive EEG acquisition hardware, the framework generates representative EEG-like signals from the temporal characteristics of the input audio.

The synthesized EEG preserves envelope variations that are useful for machine learning and optimization.

---

## 4️⃣ Feature Extraction

Multiple statistical and temporal features are extracted from the synthesized EEG.

Extracted features include:

- RMS Energy
- Peak-to-Peak Amplitude
- Envelope Characteristics
- Mean
- Standard Deviation
- Skewness
- Kurtosis
- Signal Variance
- Temporal Statistics

These features become the input for the regression model.

---

## 5️⃣ Ridge Regression

Ridge Regression is employed to establish the relationship between synthesized EEG features and reconstructed audio characteristics.

The regression model improves prediction stability while reducing overfitting.

---

## 6️⃣ Grey Wolf Optimization (GWO)

Grey Wolf Optimization is applied to optimize the regression parameters.

The optimizer searches for parameter combinations that minimize reconstruction error while improving waveform similarity.

Optimization focuses on:

- Alpha
- Window Size
- Step Size
- Learning Parameters

---

## 7️⃣ Griffin-Lim Audio Reconstruction

The optimized spectrogram is converted back into a time-domain waveform using the Griffin-Lim algorithm.

This stage generates the reconstructed lion vocalization.

---

## 8️⃣ Performance Evaluation

The reconstructed output is evaluated using several statistical metrics.

These include:

- Mean Squared Error (MSE)
- Pearson Correlation
- RMS Energy
- Peak-to-Peak Amplitude
- Skewness
- Kurtosis
- Reconstruction Accuracy

The results are presented through the graphical dashboard for easy analysis.

---

# ⚙️ System Workflow

The complete workflow of the proposed framework is illustrated below.

```text
Input Lion Audio (.wav)
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
Interactive PyQt5 Dashboard
```

---

# 🏗️ System Architecture

The proposed architecture integrates signal processing, machine learning, optimization, and visualization into a unified reconstruction framework.

```text
                     Input Audio (.wav)
                             │
                             ▼
                  Audio Preprocessing Module
                             │
                             ▼
                  Envelope Extraction Module
                             │
                             ▼
                 Synthetic EEG Generation
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
               Interactive PyQt5 Dashboard
```

---

# 🔄 Complete Processing Pipeline

Once the user clicks **Run Pipeline**, the application automatically performs the following operations:

1. Load the selected lion audio file.
2. Perform preprocessing and normalization.
3. Generate synthesized EEG signals.
4. Extract statistical and temporal features.
5. Train the Ridge Regression model.
6. Optimize reconstruction parameters using Grey Wolf Optimization.
7. Reconstruct the audio using Griffin-Lim synthesis.
8. Compute evaluation metrics.
9. Generate waveform and envelope comparisons.
10. Display EEG channel visualizations.
11. Save reconstructed audio and analysis outputs.
12. Present all results within the interactive dashboard.

The entire reconstruction process is automated, allowing researchers to execute the complete workflow through a single graphical interface.

---

# ✨ Features

The proposed framework integrates Artificial Intelligence, Signal Processing, and Optimization into a single research platform capable of reconstructing lion vocalizations from synthesized EEG signals.

## Core Features

- 🧠 EEG Signal Synthesis
- 🎵 Audio Preprocessing
- 📈 Envelope Extraction
- 🤖 Ridge Regression Model
- 🐺 Grey Wolf Optimization (GWO)
- 🔊 Griffin-Lim Audio Reconstruction
- 📊 Performance Evaluation
- 🖥 Interactive PyQt5 Desktop Dashboard
- 📂 Automatic Output Generation
- 📉 Envelope Comparison
- 📡 EEG Channel Visualization
- ▶ Audio Playback Interface
- 📑 Automatic Result Export

---

# 🖥 Interactive Desktop Dashboard

A modern desktop application was developed using **PyQt5** to simplify the complete reconstruction workflow.

The dashboard enables researchers to:

- Load audio files
- Execute the reconstruction pipeline
- Monitor execution logs
- Visualize EEG channels
- Compare envelopes
- Play reconstructed audio
- Analyze reconstruction metrics
- Access generated outputs

---

# 🏠 Dashboard Home

The home screen provides access to every stage of the reconstruction pipeline through a clean and user-friendly graphical interface.

<p align="center">
<img src="screenshots/dashboard.png" width="95%">
</p>

---

# ▶ Pipeline Execution

After selecting an input audio file, the entire reconstruction pipeline can be executed using a single button.

The dashboard displays:

- Current processing stage
- Execution progress
- Console logs
- Pipeline status
- Generated outputs

<p align="center">
<img src="screenshots/running_pipeline.png" width="95%">
</p>

---

# 📈 Envelope Comparison

Envelope comparison allows visual evaluation of how closely the reconstructed signal follows the original audio.

This comparison provides insight into reconstruction quality.

<p align="center">
<img src="screenshots/envelope_comparison.png" width="95%">
</p>

---

# 🧠 EEG Channel Visualization

The synthesized EEG channels generated during reconstruction are displayed for analysis.

Multiple channels are visualized simultaneously to observe temporal variations and signal characteristics.

<p align="center">
<img src="screenshots/eeg_channels.png" width="95%">
</p>

---

# 🔊 Audio Playback

The application allows comparison of the original and reconstructed lion vocalizations.

Users can:

- View waveform comparison
- Listen to reconstructed audio
- Analyze waveform similarity

<p align="center">
<img src="screenshots/audio_playback.png" width="95%">
</p>

---

# 📊 Performance Metrics

Following reconstruction, the dashboard automatically calculates several evaluation metrics.

These include:

- Mean Squared Error (MSE)
- Pearson Correlation
- RMS Energy
- Peak-to-Peak Amplitude
- Skewness
- Kurtosis

<p align="center">
<img src="screenshots/metrics_summary.png" width="95%">
</p>

---

# 📂 Generated Outputs

The framework automatically stores all generated outputs for future analysis.

Saved outputs include:

- Reconstructed Audio (.wav)
- Envelope Comparison
- EEG Channel Plots
- Waveform Comparison
- Performance Summary

<p align="center">
<img src="screenshots/output_folder.png" width="95%">
</p>

---

# 🎵 Sample Outputs

Representative outputs generated by the proposed framework are shown below.

---

## 🧠 EEG Channel Visualization

<p align="center">
<img src="screenshots/sample_outputs/lion_1_part_1_eeg_channels_gwo_opt.png" width="90%">
</p>

---

## 📈 Envelope Comparison

<p align="center">
<img src="screenshots/sample_outputs/lion_1_part_1_envelope_gwo_opt.png" width="90%">
</p>

---

## 🔊 Waveform Comparison

<p align="center">
<img src="screenshots/sample_outputs/lion_1_part_1_playback_gwo_opt.png" width="90%">
</p>

---

The experimental outputs demonstrate that the proposed framework is capable of reconstructing lion vocalizations while preserving important temporal characteristics and waveform structures.

---

# 📈 Performance Summary

The proposed framework demonstrates the successful integration of signal processing, optimization algorithms, and machine learning for EEG-inspired audio reconstruction.

## Evaluation Metrics

The system automatically computes several statistical metrics after each reconstruction process.

| Metric | Purpose |
|---------|---------|
| Mean Squared Error (MSE) | Measures reconstruction error |
| Pearson Correlation | Measures similarity between original and reconstructed signals |
| RMS Energy | Compares signal energy |
| Peak-to-Peak Amplitude | Measures signal amplitude variation |
| Skewness | Evaluates signal distribution |
| Kurtosis | Measures signal sharpness and distribution |

---

# 📊 Experimental Results

The experimental evaluation demonstrates that the reconstructed audio preserves important temporal characteristics of the original lion vocalization.

The combination of Ridge Regression and Grey Wolf Optimization significantly improves reconstruction quality while maintaining stable performance.

The proposed framework successfully achieves:

- High-quality waveform reconstruction
- Low reconstruction error
- Stable optimization performance
- High envelope similarity
- Effective EEG-inspired signal representation
- Automated visualization of reconstruction quality

---

# 🧪 Technologies Used

## Programming Language

- Python

---

## Desktop Application

- PyQt5

---

## Machine Learning

- Ridge Regression

---

## Optimization

- Grey Wolf Optimization (GWO)

---

## Signal Processing

- NumPy
- SciPy
- Librosa
- SoundFile

---

## Scientific Visualization

- Matplotlib

---

## Audio Processing

- Short-Time Fourier Transform (STFT)
- Griffin-Lim Algorithm

---

## Feature Engineering

- Envelope Extraction
- EEG Signal Synthesis
- Statistical Feature Extraction

---

# 📁 Repository Structure

```text
EEG-Based-Reconstruction-of-Lion-Sounds/
│
├── README.md
├── banner.png
│
├── screenshots/
│   ├── dashboard.png
│   ├── running_pipeline.png
│   ├── envelope_comparison.png
│   ├── eeg_channels.png
│   ├── audio_playback.png
│   ├── metrics_summary.png
│   ├── output_folder.png
│   │
│   └── sample_outputs/
│       ├── lion_1_part_1_eeg_channels_gwo_opt.png
│       ├── lion_1_part_1_envelope_gwo_opt.png
│       └── lion_1_part_1_playback_gwo_opt.png
│
└── LICENSE
```

---

# 🎯 Research Contributions

The major contributions of this research include:

- Development of an EEG-inspired audio reconstruction framework.
- Integration of Ridge Regression with Grey Wolf Optimization.
- Reconstruction of lion vocalizations using Griffin-Lim synthesis.
- Interactive PyQt5 desktop application for visualization.
- Automated generation of waveform comparisons and evaluation metrics.
- Scientific visualization of EEG channels and reconstructed signals.
- Modular workflow suitable for future research and experimentation.

---

# 💡 Potential Applications

The proposed framework has potential applications in several research domains:

- Brain-Computer Interface (BCI)
- EEG Signal Analysis
- Biomedical Signal Processing
- Artificial Intelligence
- Machine Learning
- Computational Neuroscience
- Audio Signal Processing
- Cognitive Science
- Speech Reconstruction Research
- Neural Signal Modeling

---

# 🚀 Future Scope

Future improvements may include:

- Integration of real EEG datasets
- Deep neural network-based reconstruction models
- Transformer-based audio reconstruction
- Diffusion models for signal generation
- Real-time EEG processing
- Multi-subject EEG analysis
- Cloud-based deployment
- Mobile application interface
- Clinical Brain-Computer Interface applications
- Emotion recognition from EEG signals
- Speech reconstruction using EEG

---

# 🔒 Research & Publication Notice

This repository represents an academic research project developed as part of my Master of Computer Applications (MCA).

The complete implementation, datasets, trained models, research manuscript, and project report are intentionally **not included** because the associated research paper is currently under editorial review.

This repository has been created exclusively to demonstrate:

- Research methodology
- System architecture
- Interactive graphical user interface
- Experimental workflow
- Sample outputs
- Performance evaluation
- Overall research contributions

Thank you for respecting the confidentiality of the unpublished research work.

---

# 🎓 Academic Information

| Item | Details |
|------|---------|
| Degree | Master of Computer Applications (MCA) |
| Project Type | Final Year Research Project |
| Academic Year | 2025–2026 |
| Research Domain | Artificial Intelligence, Machine Learning, Signal Processing |
| Application Type | Desktop Research Application |
| Development Platform | Python & PyQt5 |

---

# 📑 Research Publication

This project contributed to an ongoing research study developed as part of my MCA final-year research work.

## Research Title

**EEG-Based Reconstruction of Lion Sounds Using Ridge Regression, Grey Wolf Optimization and Griffin-Lim Audio Synthesis**

## Publication Status

🟢 **Research Manuscript Currently Under Editorial Review**

The manuscript is currently undergoing the editorial review process.

To maintain research integrity and comply with publication guidelines, the following materials are intentionally **not included** in this repository:

- Source Code
- Research Paper
- Project Report
- Datasets
- Trained Models

These materials will remain private until the publication process is completed.

---

# 🏆 Skills Demonstrated

This project demonstrates practical knowledge in:

### Programming

- Python

### Artificial Intelligence

- Machine Learning
- Optimization Algorithms

### Signal Processing

- EEG Signal Processing
- Audio Signal Processing
- Feature Extraction

### Machine Learning

- Ridge Regression
- Model Optimization

### Optimization

- Grey Wolf Optimization (GWO)

### Audio Processing

- Griffin-Lim Algorithm
- Spectrogram Processing
- Waveform Reconstruction

### Scientific Computing

- NumPy
- SciPy
- Librosa
- Matplotlib

### Desktop Development

- PyQt5
- Interactive GUI Design

---

# 📖 Keywords

Artificial Intelligence • Machine Learning • EEG • Signal Processing • Brain-Computer Interface • Audio Reconstruction • Ridge Regression • Grey Wolf Optimization • Griffin-Lim • PyQt5 • Scientific Computing • Python

---

# 🙏 Acknowledgements

I would like to express my sincere gratitude to my project mentor for his continuous guidance, encouragement, and valuable suggestions throughout the development of this research project.

### Special Thanks

**Dr. Anand Ghuli**

Project Mentor

His expertise, insightful feedback, and constant support played an important role in the successful completion of this research work.

I also express my gratitude to my institution for providing the academic environment and resources necessary to complete this project.

---

# 📬 Contact

## Rakshatha Rani

🎓 MCA Graduate

💻 Python Developer

🤖 AI & Machine Learning Enthusiast

📍 Vijayapura, Karnataka, India

📧 Email

**ranirakshatha@gmail.com**

💼 LinkedIn

https://www.linkedin.com/in/rakshatha-rani-90a11a2a3/

🌐 GitHub

https://github.com/RakshathaRani

---

# ⭐ Support

Thank you for visiting this repository.

If you found this project interesting, please consider giving it a ⭐.

Your support motivates me to continue learning, building research projects, and contributing to the developer community.

---

# 📜 Disclaimer

This repository has been created exclusively for **academic and portfolio purposes**.

The implementation source code, research manuscript, datasets, trained models, and project report are intentionally withheld because the associated research paper is currently under editorial review.

The screenshots, workflow, architecture, and experimental outputs presented in this repository are intended only to demonstrate the overall methodology and capabilities of the proposed framework.

---

<p align="center">

## 🧠 Transforming EEG Signals into Meaningful Audio Using Artificial Intelligence

### Thank you for visiting my repository!

⭐ If you found this project interesting, please consider giving it a Star.

</p>
