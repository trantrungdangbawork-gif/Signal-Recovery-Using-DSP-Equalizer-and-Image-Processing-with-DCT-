# Signal-Recovery-Using-DSP-Equalizer-and-Image-Processing-with-DCT-


## Overview

This project focuses on designing a wireless channel equalizer (inverse filter) using convolution and Z-transform techniques in Digital Signal Processing (DSP).

The system simulates how a signal is distorted after passing through a transmission channel with noise, then reconstructs the original signal using an Equalizer. In addition, the project extends DSP concepts to image processing using DCT (Discrete Cosine Transform) for image compression and reconstruction.

The implementation is developed in Python using Jupyter Notebook.

---

## Objectives

* Simulate signal distortion in wireless communication systems.
* Design an Equalizer (Inverse Filter) to recover distorted signals.
* Apply Z-transform and inverse Z-transform in DSP systems.
* Analyze reconstruction quality using MSE (Mean Squared Error).
* Extend DSP concepts to image compression using DCT.

---

## Technologies & Libraries

* Python
* NumPy
* Matplotlib
* SciPy
* scikit-image
* Jupyter Notebook
* Anaconda Navigator

---

## Main Topics

### 1. Wireless Channel Equalizer

* Linear Time-Invariant (LTI) systems
* Convolution
* Z-transform
* Inverse filtering
* Noise reduction
* Signal reconstruction

### 2. DCT Image Compression

* Discrete Cosine Transform (DCT)
* Frequency-domain image processing
* Low-frequency preservation
* Image reconstruction
* Compression quality analysis

### 3. Error Evaluation

* Mean Squared Error (MSE)
* Signal comparison
* Image quality evaluation

---

## Project Workflow

### Signal Processing

1. Generate input signal x(n)
2. Pass signal through system h(n)
3. Add white noise
4. Apply Z-transform
5. Design Equalizer W(z)
6. Recover signal x'(n)
7. Evaluate reconstruction quality using MSE

### Image Processing

1. Read grayscale image
2. Apply 2D DCT
3. Preserve low-frequency coefficients
4. Remove high-frequency components
5. Reconstruct image using inverse DCT
6. Compare image quality using MSE

---

## Features

* Custom implementation of Z-transform and inverse Z-transform.
* Wireless channel simulation with white noise.
* Signal recovery using Equalizer.
* DCT-based image compression and reconstruction.
* MSE evaluation for both signal and image processing.
* Visualization using matplotlib.

---

## Example Results

### Signal Equalization

* Distorted noisy signal successfully reconstructed.
* Recovered signal preserves waveform, frequency, phase, and amplitude characteristics.

### DCT Image Compression

* 10% frequency retention → blurred image
* 30% frequency retention → acceptable quality
* 60% frequency retention → near-original quality

---

## Future Improvements

* Use real-world wireless channel responses.
* Apply FFT/DFT based implementations.
* Integrate with embedded systems such as STM32 or ESP32.
* Extend to real audio and communication signals.
* Implement advanced image compression methods such as quantization.

---



## References

* SciPy Documentation
* Jupyter Documentation
* Research papers on DCT and DSP
* Wireless Communication & Signal Processing materials
