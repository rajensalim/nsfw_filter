# nsfw_filter
Machine Learning model to filter inappropriate (sexual) pictures

NSFW dataset from kaggle was used, containing 1476 files for training and 200 files for test.
In our case, we split the training data into 75% for training and 25% for validation.

Instead of building the model from scratch, MobileNetV2 model from transfer learning
was used and a few last output layers were added.

The idea behind this model is to predict whether the images uploaded were
sexual images or not. ~90% accuracy was obtained through this model.

Here is the link to the dataset
[https://www.kaggle.com/datasets/drakedtrex/my-nsfw-dataset](url)
