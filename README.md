# Speech Emotion Recognition
This Speech Emotion Recognition (SER) project focuses on classifying emotions from audio speech using deep learning. By leveraging publicly available datasets of emotional speech samples, the project integrates advanced audio preprocessing techniques and deep neural networks to identify emotions such as happy, sad, angry, neutral, and more. It depends solely on the emotion using the audio waves rather than words to classify sentiment. The datasets contain the exact same sentence in different emotions, which the model is able to classify.

## Datasets Used
The following datasets were employed for this project:

RAVDESS: Emotional speech and song data.

CREMA-D: Crowd-sourced multimodal emotional speech.

TESS: Toronto Emotional Speech Set.

SAVEE: Surrey Audio-Visual Expressed Emotion Dataset.

## Methodology

This project standardizes emotion labels across datasets and creates unified dataframes with file paths and labels for seamless integration. Audio features such as Mel-Frequency Cepstral Coefficients (MFCCs), chroma features, and spectral contrast are extracted using librosa. The data is then used to train LSTM/GRU-based deep learning models in TensorFlow/Keras with layers including Dense, Dropout, and recurrent layers, optimized using Adam and categorical cross-entropy loss. The model is evaluated on validation datasets with metrics such as accuracy, precision, recall, and F1-score.

Achieved **97% accuracy** on testing.


