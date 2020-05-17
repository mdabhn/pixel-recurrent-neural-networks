# Pixel Recurrent Neural Networks

> ImageNet Dataset

    Our main results also provide benchmarks on the diverse ImageNet dataset.

    There are more than 100,000 synsets in WordNet, majority of them are nouns (80,000+). In ImageNet, we aim to provide on average 1000 images to illustrate each synset. Images of each concept are quality-controlled and human-annotated. In its completion, we hope ImageNet will offer tens of millions of cleanly sorted images for most of the concepts in the WordNet hierarchy.

> One of the great advantages in generative modeling is that there are practically endless amounts of image data available to learn from.

- [ ] stochastic latent variable models such as VAE

- The autoregressive model specifies that the output variable depends linearly on its own previous values and on a stochastic term (an imperfectly predictable term).

- But to model the highly nonlinear and longrange correlations between pixels and the complex conditional distributions that result, a highly expressive sequence model is necessary.

- A two-dimensional RNN has produced very promising results in modeling grayscale images and textures.

- Theresulting PixelRNNs are composed of up to twelve, fast two-dimensional Long Short-Term Memory (LSTM) layers.

PixelRNN && PixelCNN

- https://wiki.math.uwaterloo.ca/statwiki/index.php?title=STAT946F17/Conditional_Image_Generation_with_PixelCNN_Decoders
- https://www.youtube.com/watch?v=VzMFS1dcIDs

`Long short-term memory`

Long short-term memory is an artificial recurrent neural network architecture used in the field of deep learning. Unlike standard feedforward neural networks, LSTM has feedback connections. It can not only process single data points, but also entire sequences of data.
