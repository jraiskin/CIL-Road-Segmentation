# CIL_road_seg
CIL road segmentation project repository

A lot of material has been gathered on CNN and technical knowledge
regarding Tensorflow, most of which I have not uploaded here, as I
don't believe it's of interest now.

###############################
#### General / theoretical
###############################

* YUV (colormap)
  https://en.wikipedia.org/wiki/YUV
  Might want to extract the Y channel, as is correlates with edges
* Sobel operator (edge detection convolution)
  https://en.wikipedia.org/wiki/Sobel_operator
  https://blog.saush.com/2011/04/20/edge-detection-with-the-sobel-operator-in-ruby/
  Already implemented in the code. We might want to extract features based
  on a cropped window of an image, where the Sobel operator has already been applied


###############################
#### CNN related
###############################

* Efficient Convolutional Neural Networks for Pixelwise Classification on Heterogeneous Hardware Systems

  http://arxiv.org/pdf/1509.03371.pdf
  
  Took from here the idea of reflection padding of images (p. 9)
  
* CS231n Convolutional Neural Networks for Visual Recognition
  
  http://cs231n.github.io/neural-networks-1/


###############################
#### Tensorflow related
###############################

* TensorFlow-Examples
  
  https://github.com/aymericdamien/TensorFlow-Examples
  
  Examples of code on 'familiar' datasets


###############################
#### Misc & unsorted
###############################

* Computer assisted image analysis I (Swede university course)
  
  http://www.it.uu.se/edu/course/homepage/bild1/ht15
  
  http://www.it.uu.se/edu/course/homepage/bild1/ht15/L8_classification.pdf
  
  Probably not so informative
