# Neural Style Transfer

It refers to a set of algorithms (use deep learning) which are used to manipulate or tranform images in order to adopt the appearance or visual style of another image. They are used for creation of artificial artwork from photographs, for example by transferring the appearance of famous paintings to user-supplied photographs.

# How it Works?

Two images are provide to the model as input - content image and style image. The model need to generate an output image which retains the core elements of the content image, but appears to be painted in the style of the style reference image.
The ‘encoding nature’ of CNN’s is the key in Neural Style Transfer. At each iteration, we caluclate the loss by adding content loss and style loss. Content loss measures the similarity between the activation of layers of neural network (VGG19 in our case) for content image and output image. Style loss measures the similarity between the correlations of activations of style image and output image.

![image](https://github.com/Fast-and-curious4/neural-style-transfer/assets/77771355/403588a9-4dec-4c1e-ba05-3778ba8818b4)

# Colaboratory Support

The code can be run using the following Google Colab [link](https://colab.research.google.com/drive/1u1tYtAofEAlwBKyFgHSmFDXvpGHj3cox?usp=sharing)

# Example:

## Content Image:
<img src="https://github.com/Fast-and-curious4/neural-style-transfer/assets/77771355/d751edfb-8e68-44da-a779-68f84faabdc5" width="400" height="400">

## Style Image:
<img src="https://github.com/Fast-and-curious4/neural-style-transfer/assets/77771355/f8d3cb69-bf2d-41de-8cf8-47af99633683" width="400" height="400">

## Output Image (After 1000 iterations):
<img src="https://github.com/Fast-and-curious4/neural-style-transfer/assets/77771355/fd0e5748-461b-4bd4-9e73-6d758ada8e5c" width="400" height="400">


