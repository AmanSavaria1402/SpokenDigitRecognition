# SpokenDigitRecognition

This is a project that I did as part of the assignments/case studies in the [Applied AI Course](https://www.appliedaicourse.com/) certification course.<br>
___
## Project description
The assignment was about detection of the digit being spoken by a person in an audio clip. The dataset contained around 2000 audio clips and the digit spoken in a clip.<br>
For this, an LSTM model trained on the audio signal to predict the spoken digit. There were three different approaches used for prediction:
1. Giving the raw audio signal as input to the LSTM: Worst performing model.
2. Peforming feature engineering on the raw data by converting each audio signal to a mel-spectrogram, giving this as input to the LSTM: Better performing model.
3. Performing data augmentation on the mel-spectrograms to increase the training data size, by performing time-stretching and pitch-shifting, giving this as input to the LSTM: Best performing model.

The goal of the assignment was to understand the working of an LSTM model, how to train it, the importance of feature engineering and data augmentation in deep learning applications, along with obtaining the skill to load, use and manipulate audio data.
The assignment was reviewed, graded and approved by the assigned mentor.
