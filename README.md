Hindi Fake News Dataset and Analysis
--
we have tried to extend the automation of data annotation to Hindi. This research concentrates on automating the task of identifying the links that lead to fake news and annotating it accordingly using a machine learning model. A manually annotated Hindi Fake News links dataset was used for training the model which works on algorithms such as Gaussian Naive Bayes, k-Nearest Neighbours, Support Vector Machine, LSTM and others. 


![flowchart (1)](https://user-images.githubusercontent.com/77895187/152632108-854b05d3-de97-4891-80dd-01bbafc3d692.png)

A machine-learning and a deep learning based framework to automate the process of data annotation. Our main contributions are:

First collected data from various fact check websites.
After extraction, the next step was pre-processing of data. For pre-processing we removed the punctuations and stopwords from the dataset followed by stemming and lemmatizing. Finally we vectorized the entire dataset using th TF/IDF Vectorizer.
Finally we applied baseline Machine Learning and Deep Learning Models: Gaussian Naive Bayes, Linear Regression, K-Nearest Neighbors, Support Vector Machines and Random Forest Search and Long Short-Term Memory.
The proposed models are tested on 10%, 20%, 30% and 40% test data of the dataset prepared. Our model has shown very promising results with high accuracy of 81.44% for the Random Forest model implemented on 10% test data. The highest accuracy for the LSTM model having 100 epochs and a batch size of 64 implemented on 10% test data was 64.70%.
