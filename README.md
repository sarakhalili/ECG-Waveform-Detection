# ECG Signal Waveform Detection

This project provides a comprehensive analysis of ECG signals from the MIT-BIH Arrhythmia Database. The analysis includes preprocessing, time-domain analysis, and waveform detection such as R-peaks, Q, S, P, and T points.

## Introduction

The goal of this project is to preprocess ECG signals, perform time-domain analysis, and detect key waveform components. The processed data and detected features are crucial for understanding heart function and identifying potential arrhythmias.


## Files and Directories

- **images/**: Contains images used in this README for visualization.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ECG_Signal_Analysis.git
    cd ECG_Signal_Analysis
    ```

2. Ensure you have the necessary dependencies installed:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the analysis script:
    ```bash
    python analyze_ecg.py
    ```

## Dependencies

- numpy
- pandas
- scipy
- mne
- matplotlib


