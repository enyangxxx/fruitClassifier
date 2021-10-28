# fruitClassifier
Simple RGB Histogram Classifier for Fruit Classification

This is an attempt to create a Histogram classifier that I have learned from the Computer Vision course at university. I used this dataset from Kaggle: https://www.kaggle.com/sriramr/apples-bananas-oranges. First, I only selected the subsets of good fruits, not the ones with rotten fruits. Among the good fruits, which are apple, orange and banana: I divided it into train & test set. In the test set, each fruit has 18 images, while there are about 200 train images for each fruit.

Even though I make use of the term "train", it does not indicate that the Histogram classifier would become trainable like a ML model, but the classifier uses these train images to propose how an apple or orange could look like, as histogram classifier is one of the nearest-neighbor algorithms.

This notebook walks through these essential steps:
1. Load images
2. Simple preprocessing
3. Create RGB histograms
4. Compute the shortest distance