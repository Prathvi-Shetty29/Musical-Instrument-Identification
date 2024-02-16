# 🎵 Musical Instrument Identification System

This project is aimed at building a system that can identify musical instruments from audio recordings. The system utilizes machine learning techniques to classify the audio samples into different instrument categories.

## 📖 Overview

The instrument identification system consists of several components:

1. **Data Collection**: Gathering audio recordings of various musical instruments. This dataset will serve as the basis for training our machine learning models.
   - [Kaggle](https://freesound.org/): In this dataset, we have employed a 2D representation of Music Instruments. Filename ".wav_files" contains all .wav files of different music instruments.
   
   - [Zenoda.org](https://magenta.tensorflow.org/datasets/nsynth): TinySOL is a dataset of 2913 samples, each containing a single musical note from one of 14 different instruments:audio samples for training machine learning models.

2. **Preprocessing**: Since the data obtained from the selected databases (Zenoda and Kaggle Dataset) is already clean and well-curated, no preprocessing steps are required. The audio recordings are ready for feature extraction without the need for resampling, noise reduction, or segmentation.

4. **Feature Extraction**: Extracting relevant features from the audio data, such as Mel Frequency Cepstral Coefficients (MFCCs), Chroma, and Spectral Contrast.  After extraction, each feature set is saved in a CSV file for further  model training.

5. **Model Training**: Training machine learning models  using the extracted features. The trained models will learn to classify audio samples into different instrument categories.

6. **Evaluation**: Assessing the trained models' performance through a range of metrics including accuracy, precision, recall, and F1 score. The achieved accuracy reached up to 98%.

👉For more detailed information, please refer to the [Record.pdf](Record.pdf) document.
