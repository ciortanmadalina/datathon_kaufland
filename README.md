## The Kaufland Case – Recognize the Product 

https://www.datasciencesociety.net/datathon/2018/01/30/the-kaufland-case-recognize-the-product/


## Abstract  

This paper presents a machine learning based approach for solving the business problem of identifying from pictures the products chosen by the Kaufland customers. These pictures are all taken from the same angle and typically show one or multiple products from the same category in a bag which makes the background and the bag recurrent elements.

Here we explored the method of transfer learning - using already trained and very deep NN like InceptionV3, InceptionResnetV2, VGG19, Resnet50 with combinations of retraining and no retraining of the existing layers. We solved this multiclassification problem of predicting the probabilities of each class of products by adding different final custom layers and we obtain the best result of 97.37% accuracy on a validation set of 20% (which was never seen by the training model) using the top 3 metric.

This result was achieved with the model VGG19 which distinguished itself not only for providing the best categorical accuracy but also for training speed, execution speed once deployed and reduced resource consumption.

Implementation : https://github.com/ciortanmadalina/datathon_kaufland/blob/master/GrBrGr-Kaufland.ipynb