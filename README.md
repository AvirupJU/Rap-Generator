# Rap-Generator
Implemented a simplistic Hidden Markov Model(HMM) to generate rap lyrics.
This is purely a probabilistic approach to maximise the rhyme density. The original algorithm developed by Dr. Arya McCarthy uses RankSVM and RNNs.
The RNNs determined the vector representations of words and lines that were taken from thousands of english raps. 
These were further fed into the RankSVM that predicted the next word given the previous words(similar to SVR)
This is how the word predictor of our smartphone keyboards work.

Have a look at this article for further details: https://aryamccarthy.github.io/malmi2016dopelearning/
