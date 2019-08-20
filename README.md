# Generating Stylistic Images using Convolutional Neural Networks
Major Research Project (MRP) - Ryerson University

**Abstract**
>Fine arts have long been considered a reserved mastery for the minority of talented individuals in society. The ability to create paintings using unique visual components such as color, stroke, theme, etc. is currently beyond the reach of computer algorithms. However, there exist algorithms which have the capability of imitating an artist’s painting style and stamping it on to virtually any image to create a one-of-a-kind piece. This paper introduces the concept of using a convolution neural network (ConvNet or CNN) to individually separate and recombine the style and content of arbitrary images to generate perceptually striking “art”. Given a content and style image as reference, a pre-trained VGG-16 ConvNet can extract feature maps from various layers. Feature maps hold semantic information about both reference images. Loss functions can be developed for content and style by minimizing the mean-square-error between the feature maps used. These loss functions can be additively combined and optimized to render a stylistic image. This technique is called Neural Style Transfer (NST) and it was originally developed by Leon Gatys in his 2015 research paper, “A Neural Algorithm of Artistic Style”. My MRP research attempts to replicate and improve upon the work done by Leon Gatys. The purpose of this research is to experiment using a variety of feature maps and tweaking the loss function to identify visually appealing results. A total variation loss factor is also included to minimize pixilation and sharpen feature formation. Images generated have been assigned a Mean Opinion Score (MOS) by a group of non-bias individuals to affirm the attractiveness of the results.

**Example of Neural Style Transfer**

![ScreenShot](https://codelabs.developers.google.com/codelabs/tensorflow-style-transfer-android/img/c8b30d69a632f9a2.png)

