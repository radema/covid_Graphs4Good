# covid_Graphs4Good

In this repo, I store all the notebooks and script about the Covid data analysis proposed by Kaggle \(see [CORD-19 NLP Challenge](https://www.kaggle.com/covid19)\)

My first idea was to build a search engine using Neo4j. This idea was originally thought for a search engine for arxiv papers but due to the recent events and the Kaggle's challange I decided to change my plans.
The data used in this first part are in metadata.csv file [here](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge).

On kaggle competition page there are already a lot of interesting kernels which are really good to know and learn.

Here is a short description on how I've structured this repo at the moment.

In the main page you find the following:
* a ReadMe obviously
* a notebook file with the main "result"
* a folder Model where I store all the devoleped models
* a folder Notebook where I store all the developed notebooks

## Next Steps

In this section, I list what I plan to do next. I have not planned a priority list at the moment:

* Test higher NUM_TOPIC 
* Test connector to PowerBI
* Include a similarity analisys based on Topics' distribution
* Add data from arxiv 
* Test some graph analysis on Neo4j of course