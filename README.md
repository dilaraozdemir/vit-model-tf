# Vision Transformer Model Implementation
VIT model on digit recognizer dataset.

(An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale)[https://arxiv.org/abs/2010.11929v2]

The Vision Transformer, or ViT, is a model for image classification that employs a Transformer-like architecture over patches of the image. An image is split into fixed-size patches, each of them are then linearly embedded, position embeddings are added, and the resulting sequence of vectors is fed to a standard Transformer encoder. In order to perform classification, the standard approach of adding an extra learnable “classification token” to the sequence is used.
