
# Analysis of Movies

This project is a part of the [Flatiron School Data Science Immersive Bootcamp](https://flatironschool.com/career-courses/data-science-bootcamp) Module 1. 
#### -- Project Status: [Completed]

## Project Intro/Objective

In this project, we aimed to find good business solutions to Microsoft company which is creating a new movie studio. We tried to find best genres to invest and best language films according to ratings. Then, we want to discuss these genres accoring to best profit. We aimed to find best release date of films also, and try to find whether foreign investments are needed. To find answers to this questions, we grabbed data from different sources.

### Partner
* Ezgi Gumusbas 
* Contact: Slack, Ezgi Gumusbas

* Srikanth Gungi
* Contact: Slack, Srikant Gungi

### Methods Used
* Data Grabbing via API keys
* Web Scrabing with BeautifulSoap
* Statistics

### Technologies 
* Python
* Libraries of python
* Pandas, jupyter notebook

## Project Description

First, we dive into asking questions for decision making regarding opening a new movie studio.

1. Considering the best vote average values, which genres are good to invest, and which languages also?
2. Considering the best profit, which genres are good to invest and also what is the percantage of top 5 genres?
3. Choosing a right release time-Which month of the year is best for highest revenue and when films are commonly released?
4. Investment into foreign releases and foreign marketing?

To find answers to these questions, we collected data from three different sources. Firstly, from www.themoviedb.org we grabbed two data sets. First one is for best 20 revenue films according to years. Second one is for best rated 1500 films. 
The websites has the data related to movies and we used API methodology to extract the data needed for our analysis. The genre codes and their respective words are also grabbed from the same website.

Secondly, with web scraping using BeautifulSoup we grabbed budget and revenues for movies. To do this, we used the-numbers.com website and Boxofficemojo.com.
Then, we merged them and clean them for useful format. And, plot our results for every question to see them obviously.

## Needs of this project

- Data Extraction through Web Scrapping and API methodology
- Data processing/cleaning using python
- Plotting statistical data to draw insights
- Documentation of the whole process

## Getting Started

1. Clone this repo https://github.com/ezgigm/Project_1 (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](https://github.com/ezgigm/Project_1/tree/master/Raw_Data) within this repo.   
3. Data processing/transformation scripts are being kept [here](https://github.com/ezgigm/Project_1)
4. Answers of questions can be found [here](https://github.com/ezgigm/Project_1).


## STEPS AND SOLUTIONS TO THE PROJECT
*  UPDATED DATA SET : https://github.com/ezgigm/Project_1/blob/master/last_all_data.csv
*  STEP 1 : https://github.com/ezgigm/Project_1/blob/master/STEP1_Grabbing_TMBD_best_20_highest_revenue_data.ipynb
*  STEP 2 : https://github.com/ezgigm/Project_1/blob/master/STEP2_getting_budget_with_soup.ipynb
*  STEP 3 : https://github.com/ezgigm/Project_1/blob/master/STEP3_WebScrapping_DataCollectionDocumentation.ipynb
*  STEP 4 : https://github.com/ezgigm/Project_1/blob/master/STEP4_Merging_4_different_dataframe_and_cleaning.ipynb
*  QUESTION 1 : https://github.com/ezgigm/Project_1/blob/master/Question_1_Top_Rated_Genres_and_Languages.ipynb
*  QUESTION 2 : https://github.com/ezgigm/Project_1/blob/master/Question_2_Best_Profit_Genres.ipynb
*  QUESTION 3 : https://github.com/ezgigm/Project_1/blob/master/Question_3_Best_Release_Date_According_to_Worldwide_Gross.ipynb
*  QUESTION 4 : https://github.com/ezgigm/Project_1/blob/master/Question_4_Foreign_vs_Domestic_Gross.ipynb


## Contributing DSWG Members


|Name     |
|---------|
|[Ezgi Gumusbas](https://github.com/ezgigm)| @ezgigm        |
|[Srikanth Gungi](https://github.com/srikanthgungi) |@srikanthgungi    |

## Contact 
* Our slack channel is `#houston-ds-021720`
* Feel free to contact team leads with any questions or if you are interested in contributing!
