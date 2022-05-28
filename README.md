# Vision-Transformer-Implementation

The Vision Transformer, or ViT, is a model for image classification that employs a Transformer-like architecture over patches of the image. An image is split into fixed-size patches, each of them are then linearly embedded, position embeddings are added, and the resulting sequence of vectors is fed to a standard Transformer encoder. In order to perform classification, the standard approach of adding an extra learnable “classification token” to the sequence is used.


## Model Architecture

<p float="center">
  <img src="https://www.deepdetect.com/img/blog_01_vit_arch.png" width="550" height="500" />
</p>
