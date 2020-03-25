## Food-101 Challenge

---

Food-101 is a challenging dataset consisting of 101,000 images of 101 different food classes. Even us humans would have a hard time classifying the dishes!

The original dataset can be found at : https://www.kaggle.com/dansbecker/food-101/home

This is one of the challenge problems on **fellowship.ai**. Recent SoTA is 92.5% top-1 using a Assemble-ResNet-FGVC-50.

Top-1 and Top-5 are termss used to describe the accuracy of an algorithm on a classification task. 

If the classifier’s top guess (highest probability) is the correct answer, then the correct answer is said to be in the Top-1. If the correct answer is at least among the classifier’s top 5 guesses, it is said to be in the Top-5.

Similarly, the Top-1 error is the percentage of the time that the classifier did not give the correct class the highest score. The Top-5 error is the percentage of the time that the classifier did not include the correct class among its top 5 guesses.

The **goal for this challenge** is to train a decent model with **>85% accuracy for top-1** for the test set, using a ResNet50 or smaller network with a reasonable set of augmentations.   
