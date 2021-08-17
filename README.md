# IMAGE CAPTION TELLER

## Introduction
Humans can understand an image easily but computers are far behind from humans in understanding the context by seeing an image. However, technology is evolving and various   methods have been proposed through which we can automatically generate captions for the image. 

## Motivation
- We can create a product for the blind people  which will guide them travelling on the roads without the support of anyone else. We can do this by first converting the scene into   text and then the text to voice. Both are now famous applications of Deep Learning.
- Automatic Captioning can help in making good  Google Image Search experience, as then every image could be first converted into a caption and then search can be performed based   on the caption.
- This Model can also be used in self driving cars. In the self driving cars we can use this Image caption bot which we detect the obstacle encountered in the path of self driving car.
- CCTV cameras are everywhere today, but along with viewing the world, if we can also generate relevant captions, then we can raise alarms as soon as there is some malicious activity going on somewhere.

## Libraries
![img](https://github.com/Apoorv070/Image_Caption_Generator/blob/master/libraries.PNG)

## GOAL: 
 -> **input** : Image ----------- **output** : caption generate from the given image ------------- sound conversion of text(caption)
 
## Technology used:
- Data cleaning
- Nlp
- CNN
- RNN 
- Langauage Model
- Word Embedings 
- Transfer learning 
## Applications 
- Self driving cars
- Aid to the blind : We can create a product for the blind which will guide them travelling on the roads without the support of anyone else. We can do this by first converting the   scene into text and then the text to voice
- CCTV Cameras 
- Automatic Captioning can help, make Google Image Search
## Dataset 
- I used Flickr8k Dataset to train my model if we use Flickr30k Dataset then we can get even more accuracy 
- Flickr 8k Dataset is already divided into 6000 images for training and 1000 images for validation and 1000 for testing 
- link for the Data set :-> https://www.kaggle.com/shadabhussain/flickr8k
- Glove.6b.50.d used for word embeddings which is pretrained netwok containing approximately 6billion words
- link https://www.kaggle.com/watts2/glove6b50dtxt 

## PipeLine
![img](https://github.com/Apoorv070/Image_Caption_Generator/blob/master/pipeline.PNG)


## Results obtained:
<img src="https://github.com/Apoorv070/Image_Caption_Generator/blob/master/output1.PNG" width="100" height="100">
