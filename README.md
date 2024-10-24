# Sentiment-Analysis-Modelling
Diving into the techniques used in sentiment analysis.
## Summary
In this project, multiple techniques are used to depict sentiment value specifically for wine descriptions, or reviews. Following the steps used in natural language processing models, I was able to comparen and contrast different vectorizing functions and compare their scores. I was able to prepare the data by lemmatizing, and setting classes for either positive or negative reviews using their polarity score. This then allowed me to use different vectorizers like CountVectorizer and TFIDF or term frequency-inverse document frequency. After these models, I was able to deduce a better model for average usage. Some of the testing consisted of basic percision score and classification report. This method poses excellent leverage for businesses, as it opens doors for the understanding of frequent product purchases and good ratings. This can introduce new strategies for business growth, such as quantity and stock of higher rated products, as well as what new products to develop based on data.

## Data
Our data is from winemag-data_first150k.csv, which is a file that contains information about a specific wine. Some important features consist of price, region, the variety of wine and of course the winery it originates from. The one we will be using for modelling will be description, as that is what we will use to decipher between a high or low polarity score.

## Preperation Techniques
* Wordpuncttokenizer on individual descriptions.
* TextBlob and Sentiment/polarity on each description.
* Applying 1 or 0 for classes based on polarity.
* Balancing classes for a non-biased model.

## Transforming Methods for Modelling
* CountVectorizer
* TFIDF (term frequency-inverse document frequency)

## Evaluation
The following depicts a very even score through both models using different transforming methods. 
![image](https://github.com/user-attachments/assets/61e5a61e-65bf-4f64-a2f2-4156e9eb2cab)

## Classification Report
My classification report shows even scores throughout and an even distribution between the classes predicted.
![image](https://github.com/user-attachments/assets/7d1d4269-d9ee-4c04-b251-bd07f0e3fea1)
