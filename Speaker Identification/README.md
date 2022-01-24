# Speaker Identification

In this project, we have used Speech Dataset containing the speech of 'Benjamin_Netanyau', 'Jens_Stoltenberg', 'Julia_Gillard', 'Magaret_Tarcher', 'Nelson_Mandela', 'other', and some '_background_noise_'.

Firstly we processed the data after loading it and then created the training data.

We have then mixed some noise in the training data to make it large and also close to being real.

Then we have splitted the data using train_test_split function and encoded it.

Next step we have done is **MFCC Feature Extraction**.

Then we have created a simple Sequential model based on speech feature, i.e spectrogram, melspectrogram, mfcc or simple convolutional neural network.

Then we have trained the mfcc model, predicted the output and also displayed the Confusion Matrix.
