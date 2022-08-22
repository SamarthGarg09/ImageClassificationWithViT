# Image Classification with ViT

> Dataset link [here](https://www.kaggle.com/datasets/gpiosenka/butterfly-images40-species)
 
### Description of the dataset:
* contains images of 75 species of butterfly.
* each image is of size $224*224$ pixels in JPG format.
* Train set contains 9275 images while Test set contains 375 images.
* Various data augmentation strategies has also been applied.

## Vision Transformers Architecture
<img src="images\ViT---Vision-Transformer.jpg" alt="butterfly" width="1000" height="500">

## Results and observations
* At the end of 10th epoch, the model achieves an accuracy of 93.6% on the validation set.

    * F1-score 0.781
    * precison 0.805
    * recall 0.8

<img src="images\Butterfly dataset.png" alt="butterfly" width="500" height="200">
