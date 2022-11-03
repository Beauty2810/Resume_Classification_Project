# Resume Classification Project
The goal of this project was to come up with a classification model which will predict the category of the resume. Given a resume in PDF, DOC or DOCX format, our model
extracts any form of text from the pdf or doc or docx using TIKA Library. This text was cleaned by by transformation to a better encoding scheme, removal of punctuation marks, stop words, and everything was reduced to lower case to avoid redundancy. Following the rigorous cleaning, the text was passed to our model for classification, which accurately predicts the category of resume. The overall output of our model would be the class of the input resume.

For the process of classification, a range of models were tried out ranging from Gaussian Naive Bayes, Support Vector Machines, Logistic Regression, Decision Tree Classifier, Random Forest Classifier and KNN. After repeated cleaning and training, our model was seen to perform fairly well with an overall accuracy of 93.75% using Support Vector Classifier.

# Dataset
The dataset consists of 79 resumes having different formats such as pdf, doc, docx. The resumes are labelled according to the primary category/class that a particular resume belongs to, in a csv format. We will be using this csv formatted resume dataset to train our model for classification. Our model should then be able to work on any unseen resume.

# Algorithm Flow Chart

<img width="377" alt="Screenshot 2022-11-03 163543" src="https://user-images.githubusercontent.com/108981162/199705438-bf16f8e4-8b12-4df4-b03a-0eab8bf2122e.png">

