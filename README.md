# Face Generation Project
The face generation project generates new faces that look as realistic as possible using deep convolutional generative adversarial networks ( DCGAN ). The model was trained on the CelebFaces Attributes Dataset (CelebA).
# Porject Folder Structure
The dlnd_face_generation.ipynb - Jupyter notebook that includes all the code
# Datasets
The dlnd_face_generation.ipynb Jupyter notebook include a code that downloads the dataset
# Porject Architectures
A GAN is comprised of two adversarial networks, a discriminator and a generator.
## Discriminator
The Discriminator takes real images from the input dataset and fake images from the Generator and outputs a prediction whether a given image is real or not.
## Generator
The Generator takes random noise as an input and generates samples as an output. The goal of The Generator is to generate such samples that will trick the Discriminator to think that it is seeing real images. 
# Porject Libraries 
- Pytorch 
- Numpy
- Matplotlib to Plot Images

