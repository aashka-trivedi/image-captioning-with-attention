# image-captioning-with-attention
Image Captioning System with Visual Attention

The goal of this model is to generate a caption for the given image. The model here is inspired by the paper Show, Attend, and Tell: Neural Image caption Generation with Visual attention. The dataset used is the MS COCO dataset.

This is an encoder-decoder based image captioning system using an InceptionV3 model and fully connected CNN as encoder, and recurrent neural networks (RNN), specifically a GRU, and attention-based models as a decoder.

RNNs make predictions over a sequence of input. This gives it the capability of remembering what it has seen before, so captions generated with RNNs are more informative, and considers context in a better way.

Attention models select the most relevant elements from the large input data. Here we use “Soft Attention”, similar to what was proposed by Bahadanau et al., in 2015. Soft attention gives all the image patches some weight.
