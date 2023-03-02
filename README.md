# sign_language_translator

This is tensorflow 1.0 program to detect signs language.

Part of  Data for this is extracted from american sign language dataset. Training consists of  Passing  images from  dataset through pretrained vgg16 encoder which outputs feature vectors.
These feature vectors are then fine tuned on pretrained BERT , which outputs text. I used BERT model for this task as its architecture ensures semantically,
syntactically correct output sequences, focusing on older inputs also instead of just predicting using current input.


