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


![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a young boy swinging a bat at a baseball



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a car is parked in the street with a dog



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a man is playing tennis on a clay court



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a man and a woman are playing frisbee in a field



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a group of people sitting around a table with a cake



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a zebra standing in a dirt field next to a fence



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a dog laying on a bed with a stuffed animal



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption:  a cow standing in a field next to a tree



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a blue bird sitting on top of a blue chair



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a train traveling down a track near a forest



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: an elephant standing on a cement ground next to a fence



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a teddy bear sitting next to a teddy bear



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a man in a suit and tie is talking on a cell phone



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a young man is holding a tennis racket



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a motorcycle parked on the side of a road



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a black bear walking through a field of grass



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a truck with a trailer on the back of it



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a man in a green shirt and a green shirt and a



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a remote control sitting on a table next to a remote control



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a large commercial airplane flying in the sky



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a man in a suit cases and a man in a suit



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a man is doing a trick on a skateboard



![Image2](/test2014/COCO_test2014_000000000014.jpg)

Caption: a man is playing tennis on a tennis court


### Code

The code for the ConvCap model can be found in [this Github Repo](https://github.com/jkaikaus/ie534_final)

### Contact

The creators of this new tuned model can be contacted at:  
Pulkit Dixit (pulkitd2@illinois.edu)  
Jamshed Kaikaus (kaikaus2@illinois.edu)  
Qasim Nazir (qnazir2@illinois.edu)  
Ashwin Ramesh (aramesh7@illinois.edu)    
