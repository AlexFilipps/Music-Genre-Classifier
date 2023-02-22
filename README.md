# Music-Genre-Classifier
An application which uses a LSTM neural network to classify the genre of a given piece of music.

The purpose of this project was to attempt to create, and train a neural network capable of classifying a piece of music by it's genre. 
Included file consist of:
  - The code used for network creation training and testing.
  - Some graphs generated based on the networks performance when trained with a multitude of different parameters.
  - A trained network model which performed particularly well.
  - Some sample .wav files which were used in the training and testing of the network
  
The architecture used for the network model uses a LSTM (Long-Short Term Memory) network style and accepts audio files in a .wav format. The network then returns an integer representing the genre classification it thinks the song matches most. The network was trained to identify ten different genres including blues, classical, country, disco, hiphop, jazz, metal, pop, reggae and rock.
