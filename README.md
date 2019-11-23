# Deeplearning-Style-Transfer

In this notebook, we’ll recreate a style transfer method that is outlined in the paper, Image Style Transfer Using Convolutional Neural Networks, by Gatys in PyTorch.

#Separating Style and Content
1. Style transfer relies on separating the content and style of an image. Given one content image and one style image, we aim to create a new, target image which should contain our desired content and style components:
2. objects and their arrangement are similar to that of the content image
style, colors, and textures are similar to that of the style image


# Instructions
1. Load in a pre-trained VGG Net
2. Freeze the weights in selected layers, so that the model can be used as a fixed feature extractor
3. Load in content and style images
4. Extract features from different layers of our model
5. Complete a function to calculate the gram matrix of a given convolutional layer
6. Define the content, style, and total loss for iteratively updating a target image
