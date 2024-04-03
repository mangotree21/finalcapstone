# finalcapstone
Project Name : Sentiment analysis 

Project Details:  
A dataset named ‘Consumer Reviews of Amazon Products’ from
‘Kaggle.com’ website has been used in this task. This dataset includes
information from over 34000 customer reviews for Amazon products like
the Kindle, Fire TV Stick, and more provided by Datafiniti's Product
Database. The dataset includes basic product information, rating, review
text, and more for each product. Aim of the project is used to take the 
product reviews as input and predict its sentiment.
This project uses the text blob library to use the .polarity attribute 
and .sentiment attribute which analyse the review and determines whether it
expresses a positive, negative, or neutral sentiment.

Functionality used in the project:
pre-processing :
The desired column ‘reviews. text’ is extracted from the dataset and then
checked for null values and dropped the associated rows where there are
no values.

A function named ‘pre-process ’ is used for Preprocessing data which
includes- using the spacy library for tokenization, filtering out stop words
and punctuation words, using the .lower() method, lemmatization
technique, etc.

After that another function named get_doc is used for Function to convert
pre-processed text to a SpaCy doc which contains vector value of the data.

Insights into the model's strengths and limitations:
As this model used Spacy’s en_core_web_sm which is a relatively smaller
English language package, the accuracy of the sentiment analysis could be
a little less.
On the other side, by using some functions such as:
pre-process, get_doc, analyze_sentiment this model becomes simple to
use and can predict data very quickly.

Below are the screenshots of the project:
Extracting columns from the database-
![viewing columns](https://github.com/mangotree21/finalcapstone/assets/152438509/5609e559-55f3-4744-9704-4a56a0446c13)

Data cleaning and preparing:
![data cleaning ](https://github.com/mangotree21/finalcapstone/assets/152438509/1f957293-9b3d-4fa5-80ab-4c57eb8873de)

Using functions to pre-process review data.
![functions](https://github.com/mangotree21/finalcapstone/assets/152438509/7a8fdfe6-9bd4-43b6-8dd1-69a44253ffbc)

![similarity score](https://github.com/mangotree21/finalcapstone/assets/152438509/efe5f186-cd43-4887-aa36-63d92b35de06)

