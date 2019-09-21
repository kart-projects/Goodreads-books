## Welcome to Data Analysis using CRISP-DM
In this project we will analyse the Goodreads-books dataset from kaggle website. 

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The available python notebook files should run with Anaconda distribution of Python versions 3.*.

## Project Motivation<a name="motivation"></a>

As a software developer I always wanted to develop a second hobby i.e. to read non-technical and interesting books or stories. Recently I found myself reading reviews about non-technical books on websites like Amazon and even looking for good books for my kids. During such occasion I stumbled upon https://www.goodreads.com.com and noticed that the site provides not only a good list of books to read but also questions on books to test your knowledge. When I saw the Goodreads-books dataset in Kaggle, I was immediately interested to explore it. But how do I use the CRISP-DM data mining methodology on this dataset and explore it? I wanted to spend time to do an Exploratory Data Analysis (EDA) on this dataset and at the same time also understand the CRISP-DM methodology. So, here we are with this Good-reads repo.

## What is CRISP-DM?<a name="CRISP-DM"></a>

CRISP-DM stands for Cross Industry Standard Process for Data Mining. It provides a structured approach to planning a data mining project.
The process involves six main steps for data mining.
				
                1. Business understanding
                2. Data understanding
                3. Data Preparation
                4. Modeling
                5. Evaluation
                6. Deployment
				
Our main aim with this repo is to provide a practical understanding of this methodology and not rewrite the documentation about each steps since these are available online. For a more detailed information about each steps in this methodology please read https://www.datasciencecentral.com/profiles/blogs/crisp-dm-a-standard-methodology-to-ensure-a-good-outcome.

## Things to Ponder!<a name="Questions"></a>

To to gain more insights about the Kaggle's Goodreads-books dataset I began to ponder into few questions 

               1. Which authors wrote the most books (peek into the top 10)?
		
		       2. Who are the top 10 highly rated and the bottom 5 poorly rated authors?
			   
               3. Did the books with more text reviews receive higher ratings?
		
               4. Did the ratings for Harry Potter series follow a trend?
		
               5. How was the distribution of books across languages?
			   
## File Descriptions <a name="files"></a>

There are three python notebooks attached to this repo. Each of these notebooks dive into separate parts of the CRISP-DM methodology inorder to understand the dataset well and infer useful insights from it.

1. DataExploration.ipynb - This notebook explores the data to understand the features available in data and also makes the data ready to create 
                           inferential statistics.
				
2. InferentialDataAnalysis.ipynb - This notebook looks at each features in more detail to understand their value by creating inferential  
                                   statistics like Means, Standard Deviations, Histograms and Scatterplot matrices.

3. SolveTheQueries.ipynb - This notebook helps us answer the queries we wanted to ponder by using break-down statistics and data mining if 
                           required.
			   
## Results<a name="results"></a>


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/jealousleopard/goodreadsbooks). Also I should mention that the article link explaining the CRISP-DM methodology was shared from DataScienceCentral.com website.

