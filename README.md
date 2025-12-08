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



	method	MSE	SNR_dB
0	noisy	0.324211	1.134213
1	moving_avg	0.146614	4.580737
2	FIR	0.776078	-2.656558
3	IIR	0.131809	5.043042

