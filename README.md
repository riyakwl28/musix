# musix
A music genre classifier in which the concepts of deep learning are used.For training the model the GTZAN dataset is used which consisted of 10 categories each having 100 songs.This dataset was used for the well-known paper in genre classification “ Musical genre classification of audio signals “ by G. Tzanetakis and P. Cook in IEEE Transactions on Audio and Speech Processing 2002.The audios were in .au format and has to be converted to .wav so that they are readable by the python wave module.For this the SoX module is used.This is done by the python file convert-to-wav.py by running the script on all directories containg audio files.For further processing of audios and extracting features librosa module of python was used.The audios are then converted into the spectrogram images on which cnn model was implemented.

The data is stored on google drive and i have implemented cnn with which I was able to achieve accuracy around 68%.Working futher on improving the accuracy.

