# Final-project-ROCK-Identification-
The goal of this project is to accurately predict rock name from images and text descriptions. With the objective of finding if accuracy improves with combining image and text models.

This project uses a total of 3500 images of 53 different rocks and descriptions of these rocks as input to predict rock name.

In this project the rock images are first passed through an Efficientnet classifier to determine the accuracy and probability of predicting a particular name of a rock when an image is passed through. The text descriptions for each of the 53 classes are separately treated using NLP to also determine the accuracy and probability of predicting a rock name. The output probabilities from the image and text classifiers are then combined and passed as features through a third model to observe the effect on accurately identifying a rock.  

The best image classifier was the Efficientnet_b0 and had an accuracy of 74%

![image](https://github.com/tombra1984/Final-project-ROCK-Identification-/assets/127909963/c97f3d9d-23db-4ca3-b3af-cb4f61bd2b39)

For the Text descriptions several classifiers were trained in order to identify the best classsifer based on accuracy. 

![image](https://github.com/tombra1984/Final-project-ROCK-Identification-/assets/127909963/69f2ecc3-6cd4-4f3b-8d71-3bb17d2df6ab)

The Support Vector had the best accuracy amoung all trained calssifiers with an accuracy of 74%

When the output probabilities are passed into a third model it was observed that the accuracy of predicting the rock name increased to above 95%

![image](https://github.com/tombra1984/Final-project-ROCK-Identification-/assets/127909963/4bc8c68a-8cca-4d25-9b8d-c673f52e6ff3)



