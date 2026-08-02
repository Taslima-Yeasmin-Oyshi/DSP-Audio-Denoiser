# Denoiser
🎧 A Python-based Digital Signal Processing (DSP) project for audio denoising using STFT, Spectral Subtraction, and Wiener Filtering with waveform and spectrogram visualization.

# 🎧 Audio Denoising Using DSP Techniques

A Python-based Digital Signal Processing (DSP) project that removes background noise from audio recordings using **Spectral Subtraction** and **Wiener Filtering**. The project visualizes the denoising process through waveform and spectrogram analysis, improving overall speech clarity and audio quality. :contentReference[oaicite:0]{index=0}

---

## 📌 Project Overview

Background noise significantly degrades audio quality and affects applications such as speech recognition, telecommunication, and audio restoration. This project implements a DSP-based audio denoising pipeline that estimates the noise spectrum and suppresses unwanted noise while preserving important speech components. :contentReference[oaicite:1]{index=1}

---

## 🎯 Objectives

- Design and implement a DSP-based audio denoising system.
- Reduce background noise from audio recordings.
- Compare original and denoised audio using waveform and spectrogram analysis.
- Improve speech clarity while preserving signal quality.

:contentReference[oaicite:2]{index=2}

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

- **Python**
- **NumPy**
- **SciPy**
- **Librosa**
- **Matplotlib**
- **SoundFile**
- **Google Colab**

:contentReference[oaicite:3]{index=3}

---

## 🧠 DSP Concepts Used

- Short-Time Fourier Transform (STFT)
- Spectral Subtraction
- Wiener Filtering
- Noise Power Spectral Density (PSD) Estimation
- Time-Frequency Masking

:contentReference[oaicite:4]{index=4}

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

:contentReference[oaicite:5]{index=5}

---

## 📂 Project Structure

```
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
git clone https://github.com/yourusername/Audio-Denoising-DSP.git
cd Audio-Denoising-DSP
```

Install dependencies:

```bash
pip install numpy scipy librosa matplotlib soundfile
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

:contentReference[oaicite:6]{index=6}

---

## ⚠️ Challenges

- Musical noise artifacts in spectral subtraction.
- Selecting appropriate noise-only frames.
- Handling stereo audio channels independently.

### Solutions

- Frequency and temporal smoothing.
- Automatic quiet-frame detection.
- Channel-wise denoising for stereo audio.

:contentReference[oaicite:7]{index=7}

---

## 🔮 Future Improvements

- Log-MMSE based denoising.
- Adaptive noise tracking.
- Machine Learning based speech enhancement.
- Better performance in non-stationary environments.

:contentReference[oaicite:8]{index=8}

---

## 📚 References

- S. K. Mitra — *Digital Signal Processing: A Computer-Based Approach*
- A. V. Oppenheim — *Discrete-Time Signal Processing*
- Librosa Documentation
- DSP StackExchange
- Research papers on speech denoising and Wiener filtering

:contentReference[oaicite:9]{index=9}

---

## 👥 Contributors

- **Taslima Yeasmin Oyshi**
- **Mahir Bin Hasan**
- **Abdullah Al Masum**

Department of Computer Science & Engineering  
Varendra University

:contentReference[oaicite:10]{index=10}

---

## 📄 License

This project was developed for academic and educational purposes as part of the **Digital Signal Processing Lab (CSE-416)** course. :contentReference[oaicite:11]{index=11}

---

⭐ **If you found this project useful, please consider giving it a star!**
