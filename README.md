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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/pulkitdixit/IE534_ConvCap/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Captioned Images

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
