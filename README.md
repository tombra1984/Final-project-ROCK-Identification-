# Final-project-ROCK-Identification-
The goal of this project is to accurately predict rock name from images and text descriptions. With the objective of finding if accuracy improves with combining image and text models.

This project uses a total of 3500 images of 53 different rocks and descriptions of these rocks as input to predict rock name.

In this project the rock images are first passed through an Efficientnet classifier to determine the accuracy and probability of predicting a particular name of a rock when an image is passed through. The text descriptions for each of the 53 classes are separately treated using NLP to also determine the accuracy and probability of predicting a rock name. The output probabilities from the image and text classifiers are then combined and passed as features through a third model to observe the effect on accurately identifying a rock.  

The best image classifier was the Efficientnet_B0 and had an accuracy of 74%

![image](https://github.com/tombra1984/Final-project-ROCK-Identification-/assets/127909963/c97f3d9d-23db-4ca3-b3af-cb4f61bd2b39)

