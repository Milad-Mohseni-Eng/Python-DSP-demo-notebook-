# Python-DSP-demo-notebook-
DSP Demo

# Basic DSP demo — Milad Mohseni

Short: a compact notebook that demonstrates synthetic sensor signal generation, noise injection, filtering (MA, FIR, IIR), FFT, spectrogram, and simple feature extraction.

## What
- Generate synthetic sensor data (two tones + impulse + trend)
- Add realistic noise and outliers
- Apply moving average, FIR (firwin) and IIR (butter) filters
- Compare methods by MSE and SNR
- Show spectrogram and extract simple features (RMS, peak-to-peak)

## How to run
```bash
git clone https://github.com/YourUser/YourRepo.git
cd YourRepo
python -m venv venv
venv\Scripts\activate    # Windows
pip install -r requirements.txt
jupyter lab
# open notebooks/basic_dsp.ipynb
