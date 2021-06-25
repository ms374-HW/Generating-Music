# Generating-Music
Working on generating music step by step

## One Hot Encoded Sequence Generation
Simple music generation by training a LSTM model to predict the 101st note. The predicted notes are all places at an equal time step apart, and from the generated music we can infer that they often predict the last note to repeat when trained on small datasets (1-3 MIDI files)
