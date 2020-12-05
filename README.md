# Audio-Sentiment-Analysis
This project classifies audios into 4 emotions : neutral, happy, sad, angry using Audio files of RAVDESS dataset ("https://zenodo.org/record/1188976#.X8sndWgzY2w")
1. run create_joblib to extract the features from audio files and saves it into joblib files as data and labels seperately.
2. run train_model to train model using saved joblib files using CNN giving 91.45% testing accuracy
3. run test to test any new audio file
