# Taiwanese-food-image-classification
In this project I'll try to classify 101 kinds of Taiwanese foods. This is a Kaggle competition (https://www.kaggle.com/competitions/111-1-ntut-ee-ai-hw2)

In this repository you can find two notebooks (the preprocessing one and the training one) and also a csv file with the identifiers of each class.

In the Kaggle competition we're asked to build a classifier which is able to correctly classify taiwanese food images using a dataset of 20372 images of 101 kinds of taiwanese foods. 

The images are not equally shaped therefore I've done a deep EDA and preprocessing in the first notebook in order to make them equally shaped and also to balance the classes (they are not balanced).

The algorithm I've used is the Xception algorithm pretrained on the imagenet dataset (<a style=color:blue> transfer learning </a>). The accuracy I've obtained on the test set is 77%. 

More comments in the notebooks! You can find the data in the kaggle link I've provided above. 
