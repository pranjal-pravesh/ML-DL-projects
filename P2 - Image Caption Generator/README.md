# P2 - Image Caption Generator

The objective of this project is to generate captions for input images. The dataset comprises 8,000 images, each paired with five descriptive captions. Features are extracted from both images and text captions, which are then combined to predict the next word in the caption. A Convolutional Neural Network (CNN) is used to extract image features, while a Long Short-Term Memory (LSTM) network processes the text. The model's performance is evaluated using the BLEU Score, which measures the quality of generated captions against reference captions.

Dataset link: https://www.kaggle.com/adityajn105/flickr8k
