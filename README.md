# A topic model of chord progressions
Experiments in applying variations of Latent Dirichlet Allocation to chord progressions!

Chords served hot and fresh (after being parser-boiled) from https://ddmal.music.mcgill.ca/billboard

Chord progressions are created from tokens containing chords, their durations, and their rhythmic positions using a similar collocation finding algorithm to the one used for Word2Vec (with added music cognition magic). This notebook uses Gensim to perform vanilla LDA, but the magic happens after the little functions that export to MATLAB to perform variational inference in a song-section-PMI-regularized LDA model.
