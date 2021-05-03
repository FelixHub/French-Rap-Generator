# French Rap Generator in Keras :robot: :microphone: :musical_note:

An LSTM neural network is trained to generate dope french rap lyrics 

- First, we used the Genius website API to scrapp the lyrics of over 450 french rap artists
- Then, we trained a word-level LSTM on the corpus and used it to generate rap lyrics with pretty good results
- Finally, we changed the structure of our Neural Network to be able to condition the lyrics generation by an artist name. We can see the artist's brush appearing in the resulting texts.
