MelodiCode

MelodiCode uses artificial intelligence to take on the complex task of musical composition. We built off Skuldur's work (see link below), which generated songs solely based on pitch analysis, by implementing a recurrent network that alsop analyzes patterns of rhythm, and dynamics in several piano songs and composes a song of similar style/genre.

https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5

To use: 
1. Download and open the 'MelodiCodeNN.ipynb' file in Google Colab.
2. Run the first cell to create a 'midi_songs' folder. Upload midi files of songs of your choosing into this folder. A few dozen classical songs can be found in the 'midi_songs' folder in this repo.
3. Run the second cell to train the network, which will generate a file 'test_output.mid' in the working directory. This file can be opened and played with Windows Media Player or GarageBand.
