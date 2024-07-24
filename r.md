# Lip Sync Project Report

## Introduction
The aim of this project is to synchronize audio files with a video of a speaking person using the Wav2Lip model. This process involves the use of deep learning techniques to generate realistic lip movements that match the given audio.

## Methodology
1. **Data Preparation**: We used a video file and multiple audio files for synchronization.
2. **Model**: The Wav2Lip model was utilized, leveraging its pre-trained GAN-based architecture.
3. **Inference**: The model was run with specific padding and rescaling parameters to generate the output videos.

## Experiments
- **Video**: `13_K.mp4`
- **Audio Files**: `10_S.wav`, `96_A.wav`, `96_E.wav`, `96_K.wav`
- **Parameters**: 
  - Padding: Top=10, Bottom=0, Left=10, Right=0
  - Rescale Factor: 2
  - No Smooth: Enabled

## Results
The generated videos demonstrated accurate lip synchronization with the provided audio files. Below are the output video files:
- `result_10_S.mp4`
- `result_96_A.mp4`
- `result_96_E.mp4`
- `result_96_K.mp4`

## Conclusion
The Wav2Lip model successfully synchronized the audio with the video, producing realistic lip movements. Future work could explore improving the model's performance on different types of videos and audio inputs.
