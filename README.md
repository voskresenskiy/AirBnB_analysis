
## Project motivation and description

If you are a host on AirBnB and you wanna be successful in renting your apartment, you need to know what other hosts offer on the platform and what exactly guests value in other apartments. One of the best sources of information helping to answer these questions is the website [Inside AirBnB](http://insideairbnb.com/get-the-data.html), which gives access to text descriptions written by hosts and guests' reviews. 

In the script, you can find all the preprocessing steps and analysis I have done for the [blogpost](https://medium.com/@vadimvoskresensky/how-do-berlin-neighbourhoods-differ-on-airbnb-bbf2789e9a1d) on text analysis of AirBnB hosts' descriptions and guests' reviews of Berlin apartments. The project is done in the framework of Data Scientist Nanodegree on Udacity. 

Questions I answer, with help of this analysis, are following:

- How different Berlin districts based on the text descriptions from AirBnB? 

- What are the distinctive words for the descriptions of apartments from different districts?

- What do guests of the apartments in these districts like the most?



## Data

All data I use for analysis can be collected from here: http://insideairbnb.com/get-the-data.html.

For such type of analysis, you need two files: 

- listings.csv.gz. The dataset contains all the information from the reviews of Berlin apartments. In this dataset, you can find text descriptions of the apartments, cancellation policies, number of rooms, prices, etc.

- reviews.csv.gz. The dataset contains all the reviews written by guests for Berlin apartments. 

## Results

Detailed description of the results can e found in my [blogpost](https://medium.com/@vadimvoskresensky/how-do-berlin-neighbourhoods-differ-on-airbnb-bbf2789e9a1d)

## Libraries

To successfully reproduce my script on your machine, the following packages should be installed: pandas, nltk, numpy, sklearn, seaborn, matplotlib, vaderSentiment, spacy, intertools

## Useful sources

1. [Feature selection: finding distinctive words](https://liferay.de.dariah.eu/tatom/feature_selection.html)

2. [Visualising distances of text corpora](https://liferay.de.dariah.eu/tatom/working_with_text.html#visualizing-distances)

2. [Comparing word usage in Twitter archives with help of log odds ratio in R](https://www.tidytextmining.com/twitter.html#comparing-word-usage)

3. [Named entity recognition with NLTK and SpaCy](https://towardsdatascience.com/named-entity-recognition-with-nltk-and-spacy-8c4a7d88e7da)



