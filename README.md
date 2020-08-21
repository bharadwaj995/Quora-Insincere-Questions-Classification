ITCS 6150_Machine Learning_Final project
# Quora Insincere Questions Classification-Detect toxic content to improve online conversations



### Summary

  - An existential problem for any major website today is how to handle toxic and divisive content. Quora wants to tackle this problem head-on to keep their platform a placewhere users can feel safe sharing their knowledge   with the world.Quora is a platform that empowers people to learn from each other. On Quora, people can ask questions and connect with others who contribute unique insights and quality answers. A key challenge is to weed out insincere questions -- those founded upon false premises, or that intend to make a statement rather than look for helpful answers.


### Abstract 
  - Machine learning models have been very successful when dealing with text classification problems. In this project we are tasked with classifying questions from a dataset provided by the popular website Quora, as ‘sincere’ or ‘insincere’. 
  - The large-scale dataset, provided by the website Kaggle [https://www.kaggle.com/c/quora-insincerequestions- classification/data] contains over 1,300,000 questions with labels to train our models on. A separate test set that contains over 300,000 unlabeled questions is used by Kaggle to test our model. We implement three different models, logistic regression, Naive Bayes, and recurrent neural networks, and use different pre-trained word embedding’s to achieve the best results An insincere question is defined as a question intended to make a statement rather than look for helpful answers.
  - Some characteristics that can signify that a question is insincere:
    *   Has a non-neutral tone
    * Has an exaggerated tone to underscore a point about a group of people
    * Is rhetorical and meant to imply a statement about a group of people
    * Is disparaging or inflammatory
    * Suggests a discriminatory idea against a protected class of people, or seeks confirmation of a stereotype
    * Makes disparaging attacks/insults against a specific person or group of people
    * Based on an outlandish premise about a group of people
    * Disparages against a characteristic that is not fixable and not measurable
    * Isn't grounded in reality
    * Based on false information, or contains absurd assumptions
    * Uses sexual content (incest, bestiality, pedophilia) for shock value, and not to seek genuine answers


### Methodology

    In our approach we used the Quora Insincere dataset and analyzed it. This analysis labeled datasets using the unigram feature extraction technique. We used the framework where thepreprocessor is applied to the raw sentences which make it  more appropriate to understand.Further, the different machine learning techniques trains the dataset with feature vectors and then the semantic analysis offers a large set of synonyms and similarity which provides the polarity of the content.


