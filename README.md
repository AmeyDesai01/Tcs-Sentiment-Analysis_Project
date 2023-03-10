# Tcs-Sentiment-Analysis_Project
This is a Industry level project offered by TCS called 'Automate sentiment analysis of textual comments and feedback' which I did during TCS internship. 

## Project Title:-
Automate Detection of different Sentiments from Textual Comments and Feedback.

## Project Description:-
Project Objective & Brief: To develop a deep learning algorithm to detect different types of sentiment contained in a collection of English Sentences or a large paragraph.

## Project Guidelines:-
Identify & finalize a collection of English sentences or a large paragraph which will also cover contradictory statements.
Develop a deep learning model for detection & segmentation of sentiments whether positive, negative, or neutral from the paragraph.
Test the model accuracy. Plot accuracy and loss plots.

## Expected Project Outcome:-
Algorithms to detect different types of sentiments from a paragraph.
Detailed presentation with proof of reasonable accuracy.

## Software Requirements to Implement the Project:-
Google Collab
Python, Java (opt.), Eclipse, Ubuntu OS (opt.)

**In Sentiment analysis, the data mainly focuses on whether the feedback of a product is :-**

Positive

Negative

Neutral

**This provides a top level review of the product and its acceptance in the market.**

Emotion Analysis provides a deeper insight into users' emotions.
Reading between the lines-level analysis of textual input.
Organizing input into categories and assessing its emotional content by observing words, contexts, patterns, and behaviors. This can even extend to a person's capacity for expressiveness in a given circumstance.

## Approaches to Text Classification
Rule-Based Systems:
Rule-based approaches use a collection of linguistic principles to organize text into groups.
Each rule is made up of a semantic structure and the predicted category for that pattern.

Machine Learning-based Systems:
Text classification based on past observations.
The system can learn the various relationships between text fragments and that a specific output (such as tags) is anticipated for a specific input by using training data (i.e. text).
Each text is converted into a numerical representation in the shape of a vector during feature extraction. E.g. Bag of words [A vector shows the frequency of words in a built-in dictionary]
Feature set-based training data are given to the algorithm.
The machine learning model can start to make precise predictions on unread text with comparable feature sets once it has been sufficiently trained with training samples.

## Text Classification Algorithms
The naive bayes family of algorithms, support vector machines, regressions, and deep learning algorithms with CNN and RNN are some of the most widely used machine learning techniques for building text categorization models. 
A popular techniques for assessing a text classifier's success are cross-validation, Metrics and Evaluation

It involves randomly dividing the training dataset into sets of equal length.
The remaining samples from each group (for instance, 75% of the samples) are used to train a text classifier.
On their individual sets, the classifiers make predictions, and the outcomes are compared with the human-annotated tags.
With these results, performance metrics are built, that are useful for a quick assessment of how well a classifier works.

**Performance metrics normally include:**

Accuracy: It is the proportion of texts for which the right tag was correctly predicted.

Precision: It is the proportion of correctly classified examples out of all the examples the classifier predicted for a particular tag.

Recall: It is the proportion of examples the classifier correctly predicted for a particular tag out of all the examples it should have correctly predicted.

F1 Score: It is the harmonic mean of precision and recall. 

## Test Accuracy achieved with IMDB dataset using following algorithms:
RNN- 2 LSTM Layers: 85.32% : https://colab.research.google.com/drive/1tQ8KqybhkjC1-aROrQJqj7IgWD1Mc--U

RNN- 1 LSTM Layer: 85.74% : https://colab.research.google.com/drive/1Jjsf5umzu8pvsIKDrg-pG9CtqNlMXF62

Pre-processed Text: 84.99% : https://colab.research.google.com/drive/1EjHSe1rkQB4tC5grOeixkMYgn-VSBjJ8
