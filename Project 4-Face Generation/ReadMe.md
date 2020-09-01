## Project Overview

In this project, we will define and train a DCGAN on a dataset of faces. Our goal is to get a generator network to generate new images of faces that look as realistic as possible!

The project will be broken down into a series of tasks from loading in data to defining and training adversarial networks. At the end of the notebook, we'll be able to visualize the results of our trained Generator to see how it performs; our generated samples should look like fairly realistic faces with small amounts of noise.

### Get the Data
We'll be using the [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) to train our adversarial networks.

This dataset is more complex than the number datasets (like MNIST or SVHN) we've been working with, and so, we should prepare to define deeper networks and train them for a longer time to get good results. It is suggested that you utilize a GPU for training.
