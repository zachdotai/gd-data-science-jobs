# gd-data-science-jobs
Findings from an analysis of web scraped data of data science jobs on Glassdoor in Feb 2021.

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.

## Project Motivation<a name="motivation"></a>

For this project, I was interested in using data on web scraped job postings from Glassdoor to answer a couple of questions about the data science job market:

1. Which sectors are hiring the most data science professionals at the moment?
2. Which skills do hiring companies require from different data science professionals?
3. Which skills tend to contribute the most to a higher estimated salary?
4. Does the size of the company influence the estimated salary?

We do this by initially do some high-level exploratory analysis, followed by a brief attempt to see whether a linear regression model can shed some light on the data science job market as outlined in the notebook. The dataset was complied by [Rashik Rahman](https://www.kaggle.com/rashikrahmanpritom) and can be found [here](https://www.kaggle.com/rashikrahmanpritom/data-science-job-posting-on-glassdoor).


## File Descriptions <a name="files"></a>

There is one notebook available here to showcase work related to the above questions in addition to figures pertaining to the analysis.


## Results<a name="results"></a>

The main findings of the code are summarized as follows:

- The Tech sector is the top hirer of data science professionals followed by companies in the Business Services sector.
- Python, SQL, Microsoft Excel, and Spark are the most mentioned skills in data science job descriptions.
- Posted salary somewhat correlates with size of the company (in number of employees) and revenue generated.
- Skills listed in the job description can barely explain the variance in the estimated salary.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/rashikrahmanpritom/data-science-job-posting-on-glassdoor).  Otherwise, feel free to use the code here as you would like! 
