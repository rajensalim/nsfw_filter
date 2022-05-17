# nsfw_filter
Machine Learning model to filter inappropriate picture

We use NSFW dataset from kaggle, containing 1476 files for training and 200 files for test
in our case, we split the training data into 75% for training and 25% for validation.

Instead of building the model from scratch, we use InceptionV3 model from transfer learning
and add a few last output layer.

Here is the link to the dataset
https://www.kaggle.com/datasets/drakedtrex/my-nsfw-dataset
