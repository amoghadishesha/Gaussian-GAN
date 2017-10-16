# Gaussian-GANs
For the Python dependencies, first install the requirements file:

$ pip install -r requirements.txt

If you want to also generate the animations, you need to also make sure that ffmpeg is installed and on your path.

Training

For a full list of parameters, run:

$ python gan.py --help

To run without minibatch discrimination (and plot the resulting distributions):

$ python gan.py

To run with minibatch discrimination (and plot the resulting distributions):

$ python gan.py --minibatch


This code is based on the Gaussian GANS code submitted by (https://github.com/AYLIEN/gan-intro)
For more information see the blog post: http://blog.aylien.com/introduction-generative-adversarial-networks-code-tensorflow.
