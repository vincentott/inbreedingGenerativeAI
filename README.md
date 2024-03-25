# Inbreeding: When Generative AI Starts Training on Itself

CORRIGENDUM: We made an programming error. To have the classification accuracy drop to ca. 65% (as shown on the poster), 70 (and not 10) generations are required.

A collaboration with Florian Burger & Nityah Shah.
[Read the full project report on Kaggle.](https://www.kaggle.com/code/florianburger3/master-deeplearning2023)

We built a conditional Deep Convolutional Generative Adversarial Network for the MNIST dataset.
Over 10 generations, we (1) trained the network, (2) generated some new images, and (3) replaced images in the dataset with the new ones.

Already with such simple MNIST images and a small replacement rate, inbreeding greatly reduced the quality of the images.
This finding serves as a cautionary tale: Generated data is increasingly uploaded to the internet and then used to train subsequent model generations.
How do we ensure that the internet´s future data remains useful and that future generative models do what they ought to do?
