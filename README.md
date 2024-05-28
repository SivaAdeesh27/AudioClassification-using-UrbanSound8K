# AudioClassification-using-UrbanSound8K
Welcome to the Audio Classification with UrbanSound8K repository! This repository implements a deep learning approach for classifying urban sounds using the UrbanSound8K dataset. It provides scripts for data preprocessing, model architecture design, training and evaluation, feature extraction, and visualization.

## Features
- **Data Preprocessing**: Scripts for loading, cleaning, and preparing the UrbanSound8K dataset for model training.
- **Model Architecture**: Implementation of state-of-the-art neural network architectures tailored for audio classification.
- **Training and Evaluation**: Code for training the model with support for validation and testing on unseen data.
- **Feature Extraction**: Techniques for extracting relevant audio features such as Mel-Frequency Cepstral Coefficients (MFCCs).
- **Visualization**: Tools for visualizing audio data, model performance metrics, and training history.

## [UrbanSound8K Dataset](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqay1VME1ud2JweEx5MC1Fc0EzM2JMaDhRNk1NQXxBQ3Jtc0ttdFZRRWsyTlRpYVp2cnBxLVo1OGdxUTMyZXRxT2QwNXl3ZHQtdHdHV2x5Undlcm1TRXhUbXFudThKYkc4dEtfMG56MUtYa01fNnhrbkZfTFQwNnc5Q2hDOUR0NFhWQzhaSFNoaUtlWDVfMjdkdWZqUQ&q=https%3A%2F%2Furbansounddataset.weebly.com%2Fdownload-urbansound8k.html&v=cqndT517NcQ)
The UrbanSound8K dataset consists of 8,732 short audio excerpts (<= 4 seconds) categorized into 10 classes of everyday urban sounds:
- Air conditioner
- Car horn
- Children playing
- Dog bark
- Drilling
- Engine idling
- Gunshot
- Jackhammer
- Siren
- Street music
The dataset provides a valuable resource for training and evaluating audio classification models.

## Mel-Frequency Cepstral Coefficients (MFCCs):
MFCCs are a popular feature extraction technique widely used in audio processing and speech recognition. They mimic the human auditory system's perception of sound by transforming the raw audio signal into a representation that emphasizes frequencies relevant to human hearing. This process involves the following steps:
1. **Pre-emphasis:** Highlighting high-frequency components.
2. **Framing:** Dividing the signal into short, overlapping windows.
3. **Windowing:** Applying a window function to reduce spectral leakage at the edges of each frame.
4. **Fast Fourier Transform (FFT):** Converting each frame into the frequency domain (spectrum).
5. **Mel-scale filtering:** Applying a filter bank that simulates the human auditory system's frequency response.
6. **Logarithmic compression:** Representing the energy distribution on a logarithmic scale.
7. **Discrete Cosine Transform (DCT):** Extracting cepstral coefficients, which capture the spectral envelope and enhance discrimination between sounds.
MFCCs effectively capture the characteristics of an audio signal that are most relevant for human perception, making them a powerful tool for audio classification tasks.

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

## Project Structure

AudioClassification.ipynb file contains:
- preprocessing: Scripts for loading, cleaning, and preparing the data.
- models: Implementations of deep learning architectures for audio classification.
- training: Code for training the model with validation and testing capabilities.
- features: Functions for extracting relevant audio features (including MFCCs).
- visualization: Tools for visualizing audio data, model performance metrics, and training history.
  
README.md: This file (you are reading it!).

## Usage
- Download the dataset from the link provided.
- Load the dataset to the .ipynb file and run each cell after importing all the necessary libraries.

### Let's build a symphony of sound classification together! Feel free to contribute, fork, or raise any issues. Your feedback is valuable.

