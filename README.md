# LUMINATOR
**LIGHTWEIGHT ULTRA-ADVANCED MULTI-SENSOR INTELLIGENT NOISE-ABRIDGE THREAT OVERCOMING RADAR**

---

## Problem Statement Title
**MICROPHONE ARRAY-BASED DIRECTION OF ARRIVAL OF GUNSHOT DETECTION**

It's important to know the **precise location** of a gunshot — or at least as close as humanly possible — because **gun violence** isn't going away anytime soon.  
Our goal is to **harness any available technology** or assisting capability to ensure the **best possible outcome in worst-case scenarios.**

---

## Proposed Solution

An **advanced gunshot detection and classification system** using a **hybrid approach** of:
- Microphone arrays
- FPGA-based signal processing
- Deep learning models

By leveraging **CNN-RNN neural architectures** and **Transformer layers**, we enable:
- Real-time gunshot identification
- 3D localization
- Type classification

---

## How It Solves the Problem

- Instant feedback with highly accurate 3D localization using TDOA
- Multi-classification approach to detect and identify firearm types in real-world scenarios

---

## Role of Deep Learning

- Distinguishes gunshots from other loud noises or distractions
- Reduces false alarms
- Ensures fast & accurate responses

---

### Key Features:
- Immediate detection & 3D localization
- FPGA-based noise filtering and feature extraction
- Deep learning-based classification
- Real-time responsiveness

---

## Innovation and Uniqueness

- Hybridization: Combining CNNs and RNNs for enhanced audio analysis
- Transformer Integration: Improved attention to relevant features
- Real-time Application: Live analysis of hazardous sound events

---

## Technologies Involved

### Programming Languages
- Python (ML Models)
- Verilog (FPGA Processing)

### Hardware
- 4 or 6 omnidirectional microphones
- FPGA for real-time signal processing
- GPU/TPU for model training
- LCD Display for output

### Frameworks & Libraries
- TensorFlow
- PyTorch
- Scikit-Learn
- Pandas
- TQDM

### Machine Learning Models
- CNN
- RNN (LSTM)
- Regression (TDOA)
- CNN + Fully Connected
- CST Transformer

---

## Methodology & Implementation

1. Microphone Array captures the sound
2. ADC converts it to digital signal
3. FPGA applies bandpass filtering (up to 3kHz) & extracts features
4. CNN-RNN Hybrid Model processes features
5. CST Transformer Layer applies 3 attention types:
    - Channel-MHSA: Spatial attention
    - Spectral-MHSA: Frequency-based attention
    - Temporal-MHSA: Time-based evolution attention
6. GELU Activation enhances model performance
7. Real-time output shown on display

---

## Technical Feasibility

- Built on existing technologies like FPGAs and Neural Networks
- Uses real-time signal processing and deep learning
- Feasible and scalable with current hardware

---

## Why CNN + RNN Hybrid?

### CNNs:
- Extract local patterns and hierarchies (e.g., sound textures)
- Reduce dimensionality while preserving important spatial info

### RNNs:
- Retain temporal memory
- Model long sequences (like varying gunshot durations)
- LSTM or GRU helps with temporal context in audio

---

## Model Performance Comparison

| Model               | Gunshot Detected (%) | Muzzle Blast Detected (%) | Shockwave Detected (%) | TDOA Accuracy (%) | Gun Type Classification (%) |
|--------------------|----------------------|----------------------------|-------------------------|-------------------|------------------------------|
| CNN-Only           | 65                   | 83                         | 89                      | 72                | 80                           |
| RNN-Only           | 83                   | 85                         | 94                      | 79                | 91                           |
| DNN-Only           | 82                   | 90                         | 96                      | 77                | 93                           |
| CNN+RNN            | 92                   | 93                         | 98                      | 82                | 95                           |
| CNN+RNN+CST        | 96                   | 95                         | 97                      | 89                | 98                           |

---

## Challenges & Risks

- Hardware Limitations: FPGAs have finite resources
- Latency: Real-time needs demand high processing speed
- Noise Interference: May affect accuracy
- Data Availability: High-quality gunshot datasets are rare

---

## Optimizations & Techniques

### FPGA Resource Optimization:
- Designed efficient Verilog modules
- Implemented parallel processing for real-time handling

### Algorithm Improvements:
- Developed real-time, low-latency algorithms for gunshot detection
- Integrated high-pass/low-pass filters
- Trained ML models with noise-augmented datasets

---

## References

- [FPGA Filters](https://ashrafi.sdsu.edu/PDF/filters_FPGA.pdf)  
- [Gunshot Detection Thesis - Auraria Library](https://digital.auraria.edu/files/pdf?fileid=e562b890-41f9-4170-a13b-27b07d1f1626)  
- [TDOA Localization Field Guide](https://www.decodio.com/media/downloads/TDOA_Localization_From_Theory_to_the_Field_v1-0.pdf)  
- [Multiple Impulse Acoustic Sources - MDPI](https://www.mdpi.com)  
- [Gunshot Detection Using Accelerometers - PLOS ONE](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0199023)  
- [Gun Identification using Transformer - Nature Scientific Reports](https://www.nature.com/articles/s41598-021-88594-3)  
- [Raytheon's Boomerang Acoustic System](https://prd-sc102-cdn.rtx.com/-/media/rtx/our-company/who-we-are/bbn/boomerang/files/boomerang_data.pdf)  
- [Object Tracking using TDOA - MATLAB](https://www.mathworks.com/help/dsp/ug/object-tracking-using-time-difference-of-arrival.html)  
- [Gunshot-like Sounds Detection - MDPI](https://www.mdpi.com)  
- [Postprint PDF - Google Drive](https://drive.google.com/file/d/1g3ceUoOC9cOvfQ/pdf)  
- [FireBrick Project - Tufts University](https://sites.tufts.edu/eeseniordesignhandbook/files/2017/05/FireBrick_OKeefe_F1.pdf)  
- [Indoor Gunshot Notification System - MDPI](https://www.mdpi.com)

