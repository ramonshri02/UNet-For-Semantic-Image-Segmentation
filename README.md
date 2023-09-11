# UNet For Semantic Image Segmentation

## UNet
The UNET was developed by Olaf Ronneberger et al. for Bio Medical Image Segmentation. The architecture contains two paths. First path is the contraction path (also called as the encoder) which is used to capture the context in the image. The encoder is just a traditional stack of convolutional and max pooling layers. The second path is the symmetric expanding path (also called as the decoder) which is used to enable precise localization using transposed convolutions. Thus it is an end-to-end fully convolutional network (FCN), i.e. it only contains Convolutional layers and does not contain any Dense layer because of which it can accept image of any size.

## Semantic Segmentation
Semantic segmentation refers to the process of linking each pixel in an image to a class label. These labels could include a person, car, flower, piece of furniture, etc., just to mention a few. We can think of semantic segmentation as image classification at a pixel level. For example, in an image that has many cars, segmentation will label all the objects as car objects.

# Encoder Architecture
![Alt Text]([Architecture Plots/unet_encoder.png](https://github.com/ramonshri02/UNet-for-Semantic-Image-Segmentation/blob/main/Architecture%20Plots/unet_encoder.png)https://github.com/ramonshri02/UNet-for-Semantic-Image-Segmentation/blob/main/Architecture%20Plots/unet_encoder.png)
