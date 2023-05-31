# Usupervised-Learining-ML-Projects

This Project begins with the https://drive.google.com/drive/folders/12sLEvXt5jqJRrbVhF0EsoVpVhEFTGJNN?usp=sharing where dataset is given in folders as word documents.

We got this dataset from Almabetter for our capstone project unsupervised learning.

Our dataset contains five folders with text document the text document contains various news articles by BBC.

First, we made csv file out of the folders as per instructions. The CSV has 2225 row and 2 columns. 

This is an NLP Project in which we have to identify the type of news article based on topics provided.

In this topic modelling project, we have performed all the text processing steps like changing all the text to small case, expand contraction, remove punctuation, remove special character and digits, remove stopwords and white spaces, and perform tokenization, normalization by lemmatizer and portstemmer.

To build the model we used LDA by gensim. To visualise the text importance we used pyLDAvis.

For XGboost we plotting tree plot to visualise the feature under consideration. 
We also used neural network so that deep learning can be used for topic modelling in future.

**Business Context**

In this project the task is to identify major themes/topics across a collection of BBC news articles. Using Clustering-algorithms such as Latent Dirichlet Allocation (LDA).

Dataset Description

The dataset contains a set of news articles for each major segment consisting of business, entertainment, politics, sports and technology. You need to create an aggregate dataset of all the news articles and perform topic modeling on this dataset. Verify whether these topics correspond to the different tags available.

Main Libraries used:

Pandas for data manipulation, aggregation Matplotlib and Seaborn for visualization and behavior with respect to the target variable

• Gensium for applying LDA

NumPy for computationally efficient operations

Pandas for various operations on dataframe tasks

seaborn, matplotlib for plotting graphs and charts

nltk for text pre processing
