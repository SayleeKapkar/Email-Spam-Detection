# Email-Spam-Detection
- Everyday you recieve tons of junk emails. In this project a ML based system has been developed to analyze and classify a given email as spam or not. 
- First import the necessary modules required for processing of data. 
- We then remove the duplicates from the dataset.
- We use NLP package called "stopword" which basically means useless words.
- The data is then processed by filtering out the punctuations, stopwords (useless words).
- The remaining data is then converted into a matrix of token count and split into training (80%) and testing (20%) data sets
- Train the model using Naive Bayes Classifier
- Test the accuracy of the model
