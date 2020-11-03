# Pokemon-GAN
Generating new Pokemon using a Deep Convolutional Generative Adversarial Network (DCGAN) with noise as input.
## Overview
The DCGAN used in this project is inspired from the project done Siraj Raval in his [video](https://youtu.be/yz6dNf7X7SA) and [TensorFlow DCGAN project](https://www.tensorflow.org/tutorials/generative/dcgan).
In this project the new pokemons are generated from noise input. 

There are two types of networks in this project **Generator** and **Discriminator**.

The purpose of discrimination is to classify the real pokemons from the generated pokemons and the purpose of generator is to generate the pokemons so that the discrimination would classify the generated pokemon as real pokemon.
## Dependencies
The entire code is written in google Colab as it provides free GPU and the entire code is compiled in cloud with out any pressure on the computer.
## Usage
Download the repository using the download option or
```bash
git clone https://github.com/likhit-paruchuri/Pokemon-GAN
```
Now upload the entire folder to the google drive.

Open the Untitled0.ipynb file with Colab (install Colab extension for your drive if you are using it for the first time).

Set EPOCHS and BATCH_SIZE to the desired values based on the size of dataset.

Set Continue_training to the highest value file in training_checkpoints to load the pre-trained models or set to 0 if there no pre-trained model.
## Output
The training process for the images is shown below:
<p align="center">
  <img width="400" height="400" src="https://github.com/likhit-paruchuri/Pokemon-GAN/blob/master/output.gif">
</p>
The final output at 20k EPOCH is shown below:
<p align="center">
  <img width="400" height="400" src="https://github.com/likhit-paruchuri/Pokemon-GAN/blob/master/output/img_20000.jpg">
</p>
This project is still under progress and need more training.
