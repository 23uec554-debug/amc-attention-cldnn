# Attention-Enhanced CLDNN for Automatic Modulation Classification

## Overview

This repository presents an **Attention-Enhanced Convolutional Long Short-Term Deep Neural Network (Attention-CLDNN)** for Automatic Modulation Classification (AMC) using deep learning.

The proposed architecture extends the baseline CLDNN by incorporating a temporal attention mechanism, enabling the model to focus on the most informative IQ signal features and improve classification performance, especially under challenging Signal-to-Noise Ratio (SNR) conditions.

---

## Features

- Attention-Enhanced CLDNN
- Baseline CLDNN
- Automatic Modulation Classification
- Cross-SNR Evaluation
- Low-SNR Performance Analysis
- Performance Comparison with Baseline Model

---

## Dataset

**Dataset:** RadioML2016.10b

The RadioML2016.10b dataset consists of complex IQ samples generated under multiple modulation schemes across various SNR levels.

> **Note:** The dataset is not included in this repository due to its large size.

---

## Model Architecture

The proposed network consists of:

- 1D Convolution Layers
- Batch Normalization
- Max Pooling
- LSTM Layers
- Temporal Attention Layer
- Fully Connected Layer
- Softmax Classifier

---

## Repository Contents

```
LICENSE
README.md

Modulation Detection Unified.ipynb
Modulation Detection AllSNR AttnCLDNN.ipynb

attention cldnn at 0db.png
cldnn at 0db.png
low snr accuracy.png
overall accuracy.png
```

---

## Experimental Results

This repository includes:

- **overall accuracy.png** – Overall classification accuracy comparison.
- **low snr accuracy.png** – Performance comparison under low SNR.
- **cldnn at 0db.png** – Baseline CLDNN accuracy at 0 dB.
- **attention cldnn at 0db.png** – Attention-CLDNN accuracy at 0 dB.

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

---

## Running the Project

Clone the repository:

```bash
git clone https://github.com/23uec554-debug/amc-attention-cldnn.git
```

Install the required libraries:

```bash
pip install tensorflow numpy matplotlib scikit-learn
```

Open either notebook:

```
Modulation Detection Unified.ipynb
```

or

```
Modulation Detection AllSNR AttnCLDNN.ipynb
```

Run all cells to reproduce the experiments.

---

## Future Work

- Improve cross-SNR generalization
- Evaluate additional wireless channel impairments
- Optimize the model for real-time deployment
- Deploy the trained model as a web application

---

## Author

**Jaiveer Singh**

B.Tech, Electronics and Communication Engineering

The LNM Institute of Information Technology (LNMIIT), Jaipur

---

## License

This project is licensed under the MIT License.
