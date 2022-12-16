# Basic_neural_style_transfer
Basic Implementation of neural style transfer

[Image Style Transfer Using Convolutional Neural Networks](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf), by Gatys in PyTorch.

In this paper, style transfer uses the features found in the 19-layer VGG Network, which is comprised of a series of convolutional and pooling layers, and a few fully-connected layers. In the image below, the convolutional layers are named by stack and their order in the stack. Conv1_1 is the first convolutional layer that an image is passed through, in the first stack. Conv2_1 is the first convolutional layer in the second stack. The deepest convolutional layer in the network is conv5_4.


## Separating Style and Content
Style transfer relies on separating the content and style of an image. Given one content image and one style image, we aim to create a new, target image which should contain our desired content and style components:

* objects and their arrangement are similar to that of the content image
* style, colors, and textures are similar to that of the style image

[cat](https://github.com/Bellicose-YB/Basic_neural_style_transfer/blob/main/basic_neural_style_transfer/outputs/output.png)
[alt text](image_url)
[alt text](image_url)
[alt text](image_url)
