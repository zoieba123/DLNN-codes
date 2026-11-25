# Deep Learning Experiments 7–10

This repository contains five Python programs, organized by the assignment's experiment numbers.

## Files
1. `Experiment_7_RNN_GRU.py` — One time-series forecasting experiment comparing SimpleRNN and GRU.
2. `8a_Structured_LSTM_Forecasting.py` — Structured time-series forecasting using LSTM and Bidirectional LSTM.
3. `8b_Unstructured_Audio_LSTM.py` — Unstructured audio command classification using MFCC features and LSTM.
4. `9_NLP_IMDB_LSTM_GRU.py` — NLP sentiment classification on IMDB reviews using LSTM and GRU.
5. `Experiment_10_Autoencoders.py` — One experiment containing Basic Autoencoder, Denoising Autoencoder, and Variational Autoencoder.

## Install dependencies
```bash
pip install tensorflow numpy pandas matplotlib scikit-learn librosa
```

## Dataset setup
- Experiment 7: Place `city_temperature.csv` beside the script, or edit `DATA_PATH`.
- Experiment 8A: Place `powerconsumption.csv` beside the script, or edit `DATA_PATH`.
- Experiment 8B: Extract `mini_speech_commands.zip`; update `DATASET_PATH` if needed.
- Experiment 9: IMDB downloads through `tensorflow.keras.datasets` on first run.
- Experiment 10: MNIST downloads through `tensorflow.keras.datasets` on first run.

Run each script separately. The scripts use relative dataset paths rather than the original notebook's machine-specific Windows paths.
