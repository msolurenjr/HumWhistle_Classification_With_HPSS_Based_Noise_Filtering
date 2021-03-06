### Hum and whistle classification using a Harmonic-Percussive Signal Separation (HPSS) based noise filter

This projects involves using a dataset of self-recorded hums and whistles to perform audio classification. The two notebooks contain the following:

1. **ECS7020P_miniproject_basic**: 2-label supervised classification problem where the goal is to predict the song label of a hum or whistle (either the "Harry Potter theme" or the "Imperial March" from Star Wars). [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nnH6k7hOc-eBHINapxaQP0rxfWnmBRRY)
2. **ECS7020P_miniproject_advanced**: 2-label supervised classification problem, where the goal is to label whether a hum from the MLEnd Hum and whistle dataset is meant to represent an instrumental melody (*Melody*) or a lyrical melody (*Lyric*).[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1TdI7YgYjEzUcqRBIFTVzqyl2sZiUABrX)


The main challenge here is that the hums and whistles were recorded with phone mics and hence had varying degrees of noise. Both notebooks illustrate a simple pre-processing step that attempts to remove noise by separating the harmonic part of an audio signal from its percussive part. From here, typical audio features like MFCCs, tempo, and chroma can be extracted from the cleansed audio and can be used as features for typical machine learning models (logistic regression, Random Forest, GBM, etc.).

You can access the notebooks by clicking the Colab links (recommended) or downloading the zip files from this repository.
