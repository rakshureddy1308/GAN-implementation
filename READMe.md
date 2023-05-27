# GAN IMPLEMENTATION
Generative Adversarial Networks(GAN in short) is an advancement in the field of Machine Learning which is capable of generating new data samples including Text, Audio, Images, Videos, etc. using previously available data. GANs consist of two Artificial Neural Networks or Convolution Neural Networks models namely Generator and Discriminator which are trained against each other (and thus Adversarial). We’ll discuss more this in the following section.

## HOW DOES GAN WORK?
GANs consists of two ANN or CNN models:

Generator Model: Used to generate new images which look like real images.
Discriminator Model: Used to classify images as real or fake.

## The Generator Model

The Generator Model generates new images by taking a fixed size random noise as an input. Generated images are then fed to the Discriminator Model.

The main goal of the Generator is to fool the Discriminator by generating images that look like real images and thus makes it harder for the Discriminator to classify images as real or fake.

## The Discriminator Model
The Discriminator Model takes an image as an input (generated and real) and classifies it as real or fake.

Generated images come from the Generator and the real images come from the training data.

The discriminator model is the simple binary classification model.

## Output

<img width="387" alt="2023-05-27 (3)" src="https://github.com/rakshureddy1308/GAN-implementation/assets/119916578/3651fa5c-cf37-4962-874c-57818f43d616">


