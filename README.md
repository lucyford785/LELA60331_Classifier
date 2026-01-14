# LELA60331_Classifier
Brief description:
A logistic regression classifier to sort reviews into helpful, unhelpful, and neutral categories. Review text is split into a training, development, and test set and tokenised using space based tokenisation. Tokens are one hot encoded based on a vocabulary list (learned from the training set) of length 200. Target output labels have three values: 'helpful', 'unhelpful', and 'neutral' and these are also one hot encoded. The classifier should output the probabilities that an input review belongs to a certain output class using a softmax distribution. Random seed is used such that reported results should be entirely reproducible.

Instructions to run the code:
The code in the LELA60331_Classifier.ipynb file may be run in a python 3 notebook, for testing it was run on a CPU. The dataset used is contained in the Edited_Reviews.txt file and code to download this is included in the notebook. The following packages are imported and may have to be installed onto the system prior to running the classifier: numpy, tqdm, matplotlib, Counter(from collections), re (regex), random.  

