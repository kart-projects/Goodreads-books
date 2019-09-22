## Welcome to Data Analysis using CRISP-DM
In this project we will analyse the Goodreads-books dataset from the Kaggle website. 

### Table of Contents

1. [Installation](#installation)
2. [Motivation](#motivation)
3. [What is CRISP-DM?](#CRISP-DM)
4. [Queries](#Queries)
4. [Jupyter Notebook File (*.ipynb) Descriptions](#files)
4. [Summary Results](#summaryresults)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The python notebook files in this repo should run with Anaconda distribution of Python versions 3.*.

To explore this project please download the dataset (books.csv) and the three python notebooks.

You can either upload the files using Jupyter notebook which will automatically place these files in the current working directory of your Python installation or place these files in the current working directory and then run the notebooks.

Hint: To check for the current working directory using the available notebooks just type os.getcwd() in a cell and run it. If you would like to change the current working directory before running these notebooks, use the os.chdir function, e.g. if your current working path is c:\projects, the statement you would want to execute is os.chdir("c:&#92;&#92;projects").

## Motivation<a name="motivation"></a>

As a software developer I always wanted to develop a second hobby like reading a non-technical and interesting books. Recently I found myself reading reviews about non-technical books on websites like Amazon.com. I was even looking for good books for my kid's Reading Counts tests at school. During such occasion I stumbled upon https://www.goodreads.com.com and noticed that the site provides not only a good list of books to read but also questions on books to test your knowledge of the content. When I saw the Goodreads-books dataset in Kaggle's website, I was immediately interested to explore it. But how do I use the CRISP-DM data mining methodology on this dataset and explore it? I wanted to spend time and do an Exploratory Data Analysis (EDA) on this dataset and also understand the CRISP-DM methodology. So, here we are with this Good-reads repo.

## What is CRISP-DM?<a name="CRISP-DM"></a>

CRISP-DM stands for Cross Industry Standard Process for Data Mining. It provides a structured approach to planning a data mining project.
The process involves six main steps for data mining.

![alt text](Images/CRISP-DM.png "CRISP-DM Methodology")

Our main aim with this repo is to provide a practical understanding of this methodology and not to re-write the entire documentation about each steps. These are already available online. For a more detailed information about each steps in this methodology please checkout https://www.datasciencecentral.com/profiles/blogs/crisp-dm-a-standard-methodology-to-ensure-a-good-outcome.

## Queries :thinking: <a name="Questions"></a>

To get more insights about the Goodreads-books dataset, I wanted to find answers to the following questions: 

1. Which authors wrote the most books (peek into the top 10)?

2. Who are the top 10 highly rated and the bottom 5 poorly rated authors?

3. Did the books with more text reviews receive higher ratings?

4. Did the ratings for Harry Potter series follow a trend?

5. How are books distributed across different languages?
			   
## Jupyter Notebook File Descriptions <a name="files"></a>

There are three python notebooks attached to this repo. Each of these notebooks explore separate steps of the CRISP-DM methodology to understand the dataset and infer useful insights from it.

1. **DataExploration.ipynb**
     - This notebook explores the data to understand each features individually. We perform univariate descriptive analysis on each feature to understand the data better. We create plots like Histograms and Box-plots for the quantitative variables and look at the breakdown of unique values for the qualitative variables.
				
2. **DataAnalysis.ipynb**
     - This notebook looks at each features and performs dataminig analysis on the selected input variables (X's) to predict the average rating (Y) for a book. We split the data into two sub-samples based on high and low user ratings for each books. We then train and test two models to predict average ratings on these two subset data. Finally, we understood the model quality based on  average prediction errors by looking at the Mean Absolute Error (MAE), Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).

3. **Queries.ipynb**
     - This notebook looks at the business related queries we wanted to ponder in the Queries section above by using break-down statistics and data mining techniques.
			   
## Summary Results<a name="results"></a>

The results of our data exploration involving a thorough understanding of the features are well summarized in the DataExploration.ipynb notebook. We created two Linear Regression model's and predicted the average rating of test set cases using the built model. This is all summarized in DataAnalysis.ipynb notebook. Finally, we answered our important business questions by exploring the dataset further and reaping more insights from it. This is documented in the last Python notebook Queries.ipynb. 

To get more understanding from a business use case perspective rather than reading technical analysis that was performed in this project please check out the blog post here.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/jealousleopard/goodreadsbooks). Also I should mention that the article linked here for extra reading to understand the CRISP-DM methodology was shared from the datasciencecentral website [here](https://www.datasciencecentral.com/page/search?q=CRISP+DM).

