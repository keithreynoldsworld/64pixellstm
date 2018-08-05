# 64pixellstm

The end goal of this project is to create a tensorflow model that generates newspaper comics.

I'm using tensorflowjs and jimp.

Starting small, and gradually working my way up, I started with 64/64 pixel images with either black or white pixels.

The first neural network I'm attempting to teach the computet to draw with is an LSTM (long short term memory network.)

I've created some new codecs to inteprets 12,000 images to text, and then back to a scrolling image.

I'm using TensorFlow's lstm text generation to generate new sequences in my codec and then reinterpreting them to javascript.

Once I have this mastered, then I will move to larger images, and eventually a Generative Adversarial Network for the full comic panels.

