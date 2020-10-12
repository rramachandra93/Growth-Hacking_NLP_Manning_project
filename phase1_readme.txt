Workflow

Read the video game review data. Take a look at the text of the reviews and the ratings, which you will work with in this milestone.
Note that your data is not pure JSON, but new line delimited JSON. To be able to read it, install and import ndjson.
Import Altair and pandas.
Create a plot of the ratings of the product. Study the distribution of the five categories.
Take a random sample of the reviews by selecting 1500 reviews with rating 1,
 500-500-500 reviews with ratings 2, 3, 4, and 1500 reviews with rating 5. 
This way you get a smaller balanced corpus, on which you will during Milestones 2-4.
It is recommended to use imblearn.under_sampling.RandomUnderSampler from the imbalanced-learn package, which should be first installed, then imported.
If you want to get identical results that are provided as a sample solution, use 42 as a random state.
Take a random sample of the reviews by selecting 100,000 reviews. This way you get a bigger representative corpus, on which you will work in Milestones 4 and 5.
It is recommended to use numpy.random.randint.
If you want to get identical results that are provided as a sample solution, use 42 as a random state.
Export your corpora to two separate .csv files. Both of your tables should contain a column for the reviews and a column for the ratings. 
From now on we call the review text of the JSON key reviews and the overall key ratings. Name your corpora small_corpus and big_corpus.