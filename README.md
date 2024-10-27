# Emotion Recognition Model

This repository contains an **Emotion Recognition Model** designed to classify audio data into four emotions: **sad**, **happy**, **angry**, and **neutral**. By utilizing various **acoustic features** alongside **Mel Frequency Cepstral Coefficients (MFCCs)**, this model achieved a satisfactory accuracy in recognizing emotions based on voice characteristics.

## Project Overview

Emotion recognition from audio plays an essential role in applications such as human-computer interaction, social robotics, and mental health monitoring. This model explores different combinations of acoustic features to identify the most effective feature set for detecting emotions in speech.

### Features Used

- **Acoustic Features**: These features capture different aspects of the audio signal, helping to highlight voice characteristics related to different emotions.
- **MFCCs**: Mel Frequency Cepstral Coefficients provide insights into the timbre and tonal properties of the voice, a key element for emotion detection.

Through experimenting with these features in various combinations, the model demonstrated improved performance in classifying emotions.

## Model Performance

Testing and evaluation were conducted with multiple feature combinations to assess their impact on accuracy. For an in-depth look at the model's performance, feature importance, and analysis of misclassifications, please refer to the `eval.pdf` file.

## Repository Structure

- **project.ipynb**: Contains the source code for feature extraction, model training, and testing.
- **ssp eval.pdf**: Detailed evaluation report on model performance, feature analysis, and results.
- **README.md**: Documentation of the project.
