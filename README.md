## Image Captioning using Convolutional Neural Networks
by Pulkit Dixit, Jamshed Kaikaus, Qasim Nazir, Ashwin Ramesh

### About

This website hosts the final captioned images for the MSCOCO test set obtained using a completely CNN-based approach for the **IE 534 - Deep Learning** Course at the **University of Illinois at Urbana-Champaign**.

### Approach

The inspiration for this project was the paper - *Convolutional Image Captioning* by *Jyoti Aneja, Aditya Deshpande and Alexander G. Schwing* at the University of Illinois at Urbana-Champaign. The paper was one of the first to perform image captioning on the MSCOCO dataset using only CNNs as compared to traditional approaches that used Long Short Term Memory networks (LSTMs).

For our project, we implemented a similar captioning system and aimed at improving evaluation scores by using deeper encoders, and tuning for values such as epochs, number of captions per image, temperature, etc.

### Encoders Used

To generate possibly better accuracies, we used newer and deeper encoders than the VGG16 used by the original authors, namely - 
* VGG19
* ResNext
* Wide ResNet

### Parameters Tuned

The hyperparameters tuned during our experiments are:
* Temperature
* Attention/No attention
* Beam search value
* Number of captions per image
* Number of layers in the decoder CNN module

### Captioned Images

Shown below are a few examples of images that we captioned in our test set, as compared to images captioned by the original authors:

![Image1](/test2014/COCO_test2014_000000000001.jpg)

Caption: Truck driving on a road


![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption:  a man riding a skateboard down a street


![Image2](/test2014/COCO_test2014_000000000016.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000027.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000057.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000063.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000069.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000080.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000083.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000090.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000106.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000108.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000128.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000155.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000171.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000173.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000178.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000180.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000182.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000184.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000188.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000191.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000202.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000212.jpg)

Caption:



![Image2](/test2014/COCO_test2014_000000000219.jpg)

Caption:


### Code

The code for the ConvCap model can be found in [this Github Repo](https://github.com/jkaikaus/ie534_final)

### Contact

The creators of this new tuned model can be contacted at:  
Pulkit Dixit (pulkitd2@illinois.edu)  
Jamshed Kaikaus (kaikaus2@illinois.edu)  
Qasim Nazir (qnazir2@illinois.edu)  
Ashwin Ramesh (aramesh7@illinois.edu)    
