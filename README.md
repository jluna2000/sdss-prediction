# SDSS Machine Learning Predictor Model
The Sloan Digital Sky Survey (SDSS) is a major multi-spectral imaging and spectrographic redshift survey that provides spectral data on different celestial objects.
The purpose of this repository is to access this data and train a neural network model to predict which of three categories of celestial object any particular sample is, based on spectral data associated with the sample.
The three categories of celetial object are galaxies, quasars, and stars.

**Note: This notebook was made in Google Colab, meaning that the Tensorflow version is 2.15.0. This is important to note, as some methods, such as tf.Keras.saving.load_model() are not available in later Tensorflow versions.**
