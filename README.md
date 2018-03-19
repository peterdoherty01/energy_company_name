# Energy Company Name
This project involves generating a new company name for an energy company. 
Inspired by Statoil's name change to Equinor (Source:https://www.statoil.com/en/news/15mar2018-statoil.html)

## Objectives
There were two objectives outlined:

1. Determine the reaction from the public of the new name using a sentiment analysis and display results
2. Generate a completely new company name using existing company names in the sector

## Training Set
Company names were scraped using Python from https://en.wikipedia.org/wiki/List_of_oil_exploration_and_production_companies.

## Libraries/Dependancies
1. Tflearn
2. textblob
3. tweepy

## Limitations

### Dataset
The training set did not include a full list of companies from around the world. Obviously, the bigger the training set the better. Results could be improved with a larger dataset.

### Oil
The objective of the Statoil name change was to promote a more clean energy focused company brand. The training set we used involved company names that used the word "oil". Results could be improved by taking only clean energy focused company names. Yet, this would mean a smaller dataset to train upon.

### Cleaning
1. Removed ampresand and used and
2. Removed accents
3. Removed Inc or  S.p.A. or similar which related to their incorporation structure
4. (Tanzania)Plc was removed from Swala Oil and Gas

### References
* https://www.youtube.com/watch?v=o_OZdbCzHUA
* https://github.com/kalradivyanshu/TwitterSentiment
* https://www.youtube.com/watch?v=KvoZU-ItDiE&t=2116s
* https://github.com/tflearn/tflearn/tree/master/examples
* https://opensource.com/article/17/6/collecting-and-mapping-twitter-data-using-r
* ttps://www.analyticsvidhya.com/blog/2017/03/measuring-audience-sentiments-about-movies-using-twitter-and-text-analytics/

### Licence
MIT