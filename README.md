# lstm-attention-captioning
Image Captioning using LSTMs and Atterntion

The model generates textual description of an image using both Natural Language Processing and Computer Vision. A pre-trained CNN (MobileNet v2) is used as a feature extractor. An LSTM network is used to generate the captions based on the extracted features. Attention is used to allow different words in the generated caption to depend on different parts of image.  

Implemened in PyTorch 1.4.
