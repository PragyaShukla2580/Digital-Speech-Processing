# Speech to Text Modeling

In this project, we have made use of speech data from tensorflow.org. After downloading the data, we have unzip our tar file and deleted the extra files of extracted files.

We have then done **Data Exploration and Visualization** of the word "yes". 

We found that sampling rate was 16000 Hz which we resampled to 8000 Hz.

This is a **multi-class classification** problem with classes 'bed', 'bird', 'cat', 'dog', 'down', 'eight', 'five', 'four', 'go', 'happy', 'house', 'left', 'marvin', 'nine', 'no', 'off', 'on', 'one', 'right', 'seven', 'sheila', 'six', 'stop', 'three', 'tree', 'two', 'up', 'wow', 'yes', 'zero' and  '_background_noise_'.

We found the count of each label and plotted the bar graph.

We have then found the duration of each recordings, preprocessed the audio waves, have done one-hot encoding for multi-class classification problem, splitted into train and validation dataset, built the model using Convolutional 1D and plotted the diagnostic plot. Then we loaded the best model and predicted on validation data.

We have also wrote a function for Script that prompts a user to record voice commands. It allows to record our own voice commands and test it on the model. Finally, we read the saved voice commands and converted it to text.
