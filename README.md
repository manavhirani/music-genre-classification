# Music Genre Classification using CNN
This project uses Convolutional Neural Networks (CNN) to classify music genres based on Mel-Spectrograms generated from the audio files. The dataset used is the famous [GTZAN](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification) dataset, which contains 10 genres with 100 audio files each, all having a length of 30 seconds. In addition to the audio files, the dataset also includes visual representations for each audio file in the form of Mel-Spectrograms, as well as two CSV files containing features of the audio files.

## Dataset
The GTZAN dataset is the most-used public dataset for evaluation in machine listening research for music genre recognition (MGR). The files were collected in 2000-2001 from a variety of sources including personal CDs, radio, microphone recordings, in order to represent a variety of recording conditions.

## Dependencies
This project requires the following libraries:

NumPy
Pandas
Seaborn
Matplotlib
Librosa
IPython.display
TensorFlow
Keras
sklearn
## Usage
To run this project, follow these steps:

Clone this repository
Download the dataset from Kaggle and add it to '../input/'
Install the necessary dependencies
Open the Jupyter notebook "music_genre_classifcation.ipynb"
Follow the instructions in the notebook to visualize the Mel-Spectrograms, preprocess the data, build the CNN, train the model, and evaluate the results.
