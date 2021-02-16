Keyword/Concept identification - Predict Tags

This dataset is a curated collection from Stack Exchange sites.  We will be building a model to predict the tags (a.k.a. keywords, topics, summaries), given only the question text and its title.

The dataset contains content from disparate stack exchange sites, containing a mix of both technical and non-technical questions.

Data is split in 2 files: Train and Test.

Train.csv contains 4 columns: Id, Title, Body, Tags

Id - Unique identifier for each question

Title - The question's title

Body - The body of the question

Tags - The tags associated with the question (all lowercase, should not contain tabs '\t' or ampersands '&')

Test.csv contains the same columns but without the Tags, which we have to predict.

The questions are randomized and contains a mix of verbose text sites as well as sites related to math and programming.

The number of questions from each site may vary, and no filtering has been performed on the questions (such as closed questions).


Link to the dataset and source:

https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/overview