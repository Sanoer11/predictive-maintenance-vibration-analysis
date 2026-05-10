# Predictive Maintenance using Vibration Analysis

A DSP-to-ML predictive maintenance system for electric motor fault detection using vibration signal analysis, feature engineering, FFT, Continuous Wavelet Transform (CWT), and ensemble machine learning in MATLAB.

---

## Features

- Vibration-based motor fault detection
- Butterworth bandpass filtering
- FFT frequency-domain analysis
- Continuous Wavelet Transform (CWT)
- Statistical feature extraction
- Ensemble Bagged Decision Tree classifier
- 10-Fold Cross Validation
- Confusion matrix visualization
- Feature importance analysis
- Synthetic vibration signal generation

---

## Technologies Used

- MATLAB
- Machine Learning
- Digital Signal Processing (DSP)
- FFT
- Continuous Wavelet Transform (CWT)

---

## Project Workflow

1. Load vibration dataset
2. Apply Butterworth bandpass filtering
3. Segment signals into 1-second windows
4. Extract time-domain and frequency-domain features
5. Train ML classifier
6. Evaluate performance using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
7. Visualize FFT, CWT, and confusion matrix

---

## Extracted Features

### Time-Domain Features
- Mean
- RMS
- Variance
- Kurtosis
- Crest Factor
- Skewness

### Frequency-Domain Features
- Max Frequency
- Spectral Energy

---

## Machine Learning Model

- Ensemble Bagged Decision Trees
- 10-Fold Cross Validation
- Fault classification:
  - Normal
  - Faulty

---

## Results

- Achieved ~95–100% classification accuracy
- Successfully identified harmonic fault signatures
- Detected characteristic fault frequencies near 300 Hz
- Improved robustness using statistical and spectral features

---

## Frequency Analysis

FFT comparison between healthy and faulty motor signals:

![FFT Comparison](results/fft_comparison.png)

---

## Confusion Matrix

![Confusion Matrix](results/confusion_matrix.png)

---

## Continuous Wavelet Transform (CWT)

![CWT Analysis](results/cwt_analysis.png)

---

## Repository Structure

```bash
predictive-maintenance-vibration-analysis/
│
├── data/
├── src/
├── results/
├── docs/
├── report/
└── README.md
```

---

## How to Run

1. Open MATLAB
2. Clone the repository

```bash
git clone https://github.com/your-username/predictive-maintenance-vibration-analysis.git
```

3. Place vibration dataset inside `data/`
4. Run:

```matlab
predictive_maintenance.m
```

---

## Future Improvements

- Deep learning-based fault classification
- Real-time sensor streaming
- Edge deployment on Raspberry Pi
- CNN/LSTM hybrid models
- IoT integration for industrial monitoring

---

## Author

Sanoer Soni  
AI/ML & Embedded Systems Developer

- LinkedIn: https://linkedin.com/in/sanoer
- GitHub: https://github.com/Sanoer11

---
