# Videoclip Retrieval VAE Framework

1. Description: This repo contains a content retrieval framework for finding the k-most similar video clips based on a user query. A user defined query is a music video clip of their choise which is given as an input. The video-input is then passed through a audio feature extractor and a visual video extractor so that a combined audio-visual feature vector is created. This particular implentation is based on a variational auto encoder for similarity score extraction by comparing the latent representation of the query-input to the a pre stored latent representation of a number of songs.

2. How to install: This project contains several files which are "stand-alone", meaning they can be run individualy, as long as the proper filepaths are given. For example, a user should point the feature extractors to the location of his video file. Functionality for extracting the .wav file from the video file has not been implemented yet, so the user should use the ffmpeg library in order to extract the raw audio files for the audio extractor.

3. Requirements: This project relies on several python libraries for execution which can be found in the "requirements.txt". Notably, we used two particual useful libraries for extracting the video features (openAI - CLIP) and audio features (pyAudioAnalysis).
