# python-assignment-for-cruv
LIBRARIES USED:
math, pandas, numpy, regex, NLTK and SKLEARN.

DATASET:
The dataset consists of 5 main columns, Title, Content, Published_at, Source and Topic.
Title and Content are the only columns containing text.
Content already consists of the topics included in Title.

METHOD:
Iterated through the dataset document using pandas and stored it in a variable 'msg'.
Used stopwords and lemmatization to clean up the dataset and appended to list 'corpus'.
Divided the corpus into train set and test set(90-10).

Calculated Term Frequency 
Calculated Inverse Document Frequency
Calculated TF-IDF

Used test set to calculate TF-IDF
