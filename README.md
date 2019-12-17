# Abstract:
With the surge of spam content on smartphones, there is a necessity to build a spam filter for text messages as
accurately as possible. Traditional email spam filters cannot be used for text messages as most of the emails
contain full sentences, common-source, and a subject line whereas, text messages tend to contain incomplete
sentences and are misspelled. This project seeks to build a spam classifier using Bayes theorem with other
variations to predict the nature of an incoming text message.
# 1.Introduction:
Spam content is increasing more and more in text messages with recent developments in technology. A recent
survey from Techjury found that text messages have 209% higher response rates than emails, and 23 billion texts
are sent globally every day. It is important to detect spam messages not only for personal convenience but also for
security. Being able to remove texts with potential viruses or malicious intent of any kind is necessary on both
individual user levels and larger scales. Email service providers use a spam filter which automatically filters out
highly potential spam emails but, such advanced filters are not available in text messaging.
Many machine learning techniques such as KNN ( Clustering), Random forest, SVM, Gradient boosting, Naïve
Bayes, etc. can be used to classify the text messages. All the methods except Naïve Bayes convert the text
messages into word vectors and use the words as features. For example, the KNN algorithm considers the
Euclidian distance between two texts as a parameter, and the Random forest generates multiple decision trees
based on the word frequencies to classify the text message. On the other hand, Naïve Bayes uses the word
frequency to calculate the individual probability of words to estimate the probability of a text being spam, which
makes it powerful for the small amounts of data.
This project analyzes a sample data set of text messages which are prelabeled and implements Bayes theorem in
determining the spam nature of any text message. The organization of this project will be as follows, Section 2
describes the dataset and cleaning process; Section 3 shows the descriptive statistics of the data; Section 4
contains the description of the methodology using Bayes theorem. Results of the project and future extensions are
described in Section 5 and Section 6 respectively.
