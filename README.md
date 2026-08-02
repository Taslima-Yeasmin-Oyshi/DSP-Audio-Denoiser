# 🎧 Audio Denoising Using DSP Techniques

A Python-based Digital Signal Processing (DSP) project that removes background noise from audio recordings using **Spectral Subtraction** and **Wiener Filtering**. The project visualizes the denoising process through waveform and spectrogram analysis, improving overall speech clarity and audio quality.

---

## 📌 Project Overview

Background noise significantly degrades audio quality and affects applications such as speech recognition, telecommunication, and audio restoration. This project implements a DSP-based audio denoising pipeline that estimates the noise spectrum and suppresses unwanted noise while preserving important speech components.

---

## 🎯 Objectives

- Design and implement a DSP-based audio denoising system.
- Reduce background noise from audio recordings.
- Compare original and denoised audio using waveform and spectrogram analysis.
- Improve speech clarity while preserving signal quality.

---

## ✨ Features

- 🎵 Stereo & Mono Audio Support
- 📊 Short-Time Fourier Transform (STFT)
- 🔊 Automatic Noise Spectrum Estimation
- 🎚 Spectral Subtraction
- 🎛 Wiener Filtering
- 📈 Waveform Visualization
- 🌈 Spectrogram Visualization
- 💾 Save Denoised Audio Output

---

## 🛠 Technologies Used

- Python
- NumPy
- SciPy
- Librosa
- Matplotlib
- SoundFile
- Google Colab

---

## 🧠 DSP Concepts Used

- Short-Time Fourier Transform (STFT)
- Spectral Subtraction
- Wiener Filtering
- Noise Power Spectral Density (PSD) Estimation
- Time-Frequency Masking

---

## ⚙️ Processing Pipeline

1. Load stereo or mono audio.
2. Normalize the audio signal.
3. Apply Short-Time Fourier Transform (STFT).
4. Estimate the noise spectrum.
5. Apply Spectral Subtraction or Wiener Filtering.
6. Smooth the gain mask.
7. Reconstruct the signal using inverse STFT.
8. Visualize waveform and spectrogram.
9. Save the denoised audio.

---

## 📂 Project Structure

```text
Audio-Denoising-DSP/
│
├── input_audio/
├── output_audio/
├── images/
├── notebook.ipynb
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Taslima-Yeasmin-Oyshi/Denoiser.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

1. Place your input audio file inside the project folder.
2. Update the input file path in the code.
3. Run the notebook or Python script.
4. The denoised audio will be generated and saved automatically.

---

## 📊 Results

The implemented system successfully:

- Reduces stationary background noise.
- Produces cleaner waveforms.
- Generates clearer spectrograms.
- Improves overall speech clarity.
- Preserves important speech information.

---

## ⚠️ Challenges

- Musical noise artifacts in spectral subtraction.
- Selecting appropriate noise-only frames.
- Handling stereo audio channels independently.

### Solutions

- Frequency and temporal smoothing.
- Automatic quiet-frame detection.
- Channel-wise denoising for stereo audio.

---

## 🔮 Future Improvements

- Implement Log-MMSE based denoising.
- Add adaptive noise tracking.
- Integrate machine learning-based speech enhancement.
- Improve performance in non-stationary environments.

---

## 📚 References

1. S. K. Mitra — *Digital Signal Processing: A Computer-Based Approach*
2. A. V. Oppenheim — *Discrete-Time Signal Processing*
3. Librosa Documentation
4. DSP StackExchange
5. Research papers on speech denoising and Wiener filtering

---

## 👥 Contributors

- Taslima Yeasmin Oyshi
- Mahir Bin Hasan
- Abdullah Al Masum

**Department of Computer Science & Engineering**  
**Varendra University**

---
## 📄 Project Report

The complete project report is available below.

📥 **[View Project Report](DENOISER.pdf)**

## 📄 License

This project was developed for academic and educational purposes as part of the **Digital Signal Processing Lab (CSE-416)** course.

---

⭐ **If you found this project useful, please consider giving it a star!**
