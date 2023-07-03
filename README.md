# Videoclip Retrieval VAE Framework


1. Description: This repo contains a content retrieval framework for finding the k-most similar video clips based on a user query. A user defined query is a music video clip of their choise which is given as an input. The video-input is then passed through a audio feature extractor and a visual video extractor so that a combined audio-visual feature vector is created. This particular implentation is based on a variational auto encoder for similarity score extraction by comparing the latent representation of the query-input to the a pre stored latent representation of a number of songs.
