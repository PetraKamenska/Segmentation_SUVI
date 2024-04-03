## Deep learning for segmentation on SUVI images

### ABSTRACT
There are several reasons for observing the Sun and its corona. The main one is the forecast of space weather, which can affect technologies on Earth and in space. Coronal holes are an important coronal phenomenon, for which we created an automatic segmentation model. We segmented coronal holes in images from the latest SUVI telescope, which has been scanning the Sun since 2019. The resulting model is complex and can correctly segment phenomena in images from other telescopes. The architecture of the SCSS-Net model was used for the model. The result of our work is also a preprocessed dataset of all available images from the SUVI telescope, which can be used for further research.  


### STRUCTURE
- [prerequisites](prerequisites/) contains steps for downloading data and installing necessary libraries
- after downloading images provided in [prerequisites notebook](prerequisites/prerequisites.ipynb), [data folder](data/) should contain images for this project
- [modeling folder](modeling/) contains notebooks used for analysis regarding segmentation of coronal holes
- [src folder](src/) contains SCSS-net convolutional neural network from https://arxiv.org/pdf/2109.10834.pdf 
- [preprocessing folder](preprocessing/) contains code and scripts to preprocess data. There is no need for user to run those scripts again.
- [figures](figures/) contains important figures.

