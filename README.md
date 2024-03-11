# GAN
Generative Adversarial Networks for Fashion

## What is a Generative Adversarial Network (GAN)
Designed in 2014, a Generative Adversarial Network (GAN) is a Machine Learning framework that is designed to generate synthetic images that are similar to the input data. A GAN consists of two main components- the Generator and the Discriminator. The Generator takes in random noise and generates images that resemble the dataset. The goal of the Generator is to create realistic looking images to fool the Discriminator. The Discriminator is designed to differentiate between fake (images produced by the Generator) and real images (from the dataset). The discriminator aims to minimize its loss function by updating itself to more accurately determine a fake/real image. The training process of a GAN involves a kind of competition between the Generator and the Discriminator, which is why it's called "adversarial." The Generator tries to fool the Discriminator and the Discriminator keeps getting more accurate with each iteration. Essentially, the Generator aims to perfect its art of deception, while the Discriminator evolves to become a better judge.

<img width="470" alt="DiscriminatorTraining" src="https://github.com/hsualexotake/Deep-Learning-GAN/assets/147958762/23f45c62-4d70-4eb7-b698-702107c510f5">

In my version of creating a GAN, I used TensorFlow's Fashion-MNIST dataset to train a generator/Discriminator to produce synthetic images. The Fashion-MNIST consists of 28x28 grayscale images of 10 fashion categories, such as shirts, dresses, shoes, and bags. The primary goal of this project is to explore the capabilities of GANs in generating realistic synthetic images of clothing items. Through this endeavor, we aim to demonstrate the potential of GANs in creative and commercial applications, such as fashion design and virtual clothing modeling.

## Dependencies
TensorFlow 2.8.0
