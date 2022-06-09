# Natural_Language_Processing_Document_Clustering

Document clustering consist of assigning a given document to its right category/cluster. In this project, we consider a set of unlabeled articles downloaded from wikipedia (extensible to private documents), learn meaninful features and cluster them based on their similarities using K-Means clustering. The Elbow method has been used to determine the optimal value of K. During the processing stage, each article is represented as a vector using the TF-IDF (TfidfVectorizer).

# Dataset
The dataset is composed of articles downloaded from wikipedia covering sports, finance, computer science, technology topics. They are in particular related to the American football, computer vision object detection object classification, badminton, data science, artificial intelligence, deep learning, European central bank, chatbot virtual assistant, finTech financial technology, cryptocurrency, basketball, soccer.

![dowload_dataset](https://user-images.githubusercontent.com/48753146/172749356-074ff67a-4158-4c4a-a9ab-640c01c3d07c.PNG)

# Data Cleaning
Natural language processing data cleaning techniques have been applied to the dataset before the clustering.
 - Punctuation Removal
 - Drop Numbers
 - Lower all Words for consistency
 - Lemmatization
 - Removal of Stop Words

# Required Dependencies
 - Pandas
 - Wikipedia
 - Tweepy
 - Re
 - Textblob
 - Matplotlib
 - NLTK (dowload wordnet and omw-1.4)


# Clustering Result
![Capture](https://user-images.githubusercontent.com/48753146/172750809-83d8c27f-7b8b-4605-8bc4-6e87411af84d.PNG)
