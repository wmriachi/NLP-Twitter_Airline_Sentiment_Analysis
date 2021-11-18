# Natural Language Processing -Twitter Airline Sentiment Analysis

Context
Background and Context:

Twitter posses 330 million monthly active users, which allows businesses to reach a broad population and connect with customers without intermediaries. On the other side, there’s so much information that it’s difficult for brands to quickly detect negative social mentions that could harm their business.

That's why sentiment analysis/classification, which involves monitoring emotions in conversations on social media platforms, has become a key strategy in social media marketing.

Listening to how customers feel about the product/services on Twitter allows companies to understand their audience, keep on top of what’s being said about their brand, and their competitors, and discover new trends in the industry.

Data Description:

A sentiment analysis job about the problems of each major U.S. airline. Twitter data was scraped from February of 2015 and contributors were asked to first classify positive, negative, and neutral tweets, followed by categorizing negative reasons (such as "late flight" or "rude service").

High Level Steps to be Followed
Steps and tasks:

* Import the libraries, load dataset, the print shape of data, data description. 
Understand of data columns: 
** a. Drop all other columns except “text” and “airline_sentiment”.
** b. Check the shape of the data.
** print the first 5 rows of data.
* Text pre-processing: Data preparation. 
** NOTE:- Each text pre-processing step should be mentioned in the notebook separately.
** a. Html tag removal.
** b. Tokenization.
** c. Remove the numbers
** d. Removal of Special Characters and Punctuations.
** e. Removal of stopwords
** f. Conversion to lowercase.
** g. Lemmatize or stemming.
** h. Join the words in the list to convert back to text string in the data frame. (So that each row contains the data in text format.)
i. Print the first 5 rows of data after pre-processing.
Vectorization: 
a. Use CountVectorizer.
b. Use TfidfVectorizer.
Fit and evaluate the model using both types of vectorization. 
Summarize your understanding of the application of Various Pre-processing and Vectorization and the performance of your model on this dataset. 
7.Overall notebook should have:
a. Well commented code
b. Structure and flow
