
Movie Analysis  

Kennedi White 

## Overview 
Movies are an important part of our everyday life and we seek them out for enjoyment and fulfillment, but what makes a successful movie? The business problems is that Microsoft needs us to help familiarize them with the film industry, and provide recommendations to get them started in creating successful movies. We take a deeper look into the highest average ratings per movie, the top rated movies overall and the number of ratings to see if there are any correlations or comparisons we can obtain. This analysis will give Microsoft a better picture into what movies are doing well and draw insights into potential reason why. The data used to help provide insight into this business problems was imported pandas as pd, and the three files: 
1.df = pd.read_csv('data/zippedData/imdb.title.basics.csv.gz
2.df2 = pd.read_csv('data/zippedData/imdb.title.ratings.csv.gz
3.df3 = pd.read_csv('data/zippedData/bom.movie_gross.csv.gz

The methods used are importing pandas and required dataframes used for analysis, merging of data frames on common and unique identifiers, as well as visual representations of histograms, descriptive statistics and correlation plots for insight.  


A one-paragraph overview of the project, including the business problem, data, methods, results and recommendations.

## Business Problem

Summary of the business problem you are trying to solve, and the data questions that you plan to answer in order to solve them.

***
Questions to consider:
* What are the business's pain points related to this project?
* How did you pick the data analysis question(s) that you did?
* Why are these questions important from a business perspective?
***

## Data

Describe the data being used for this project.
The data came from the specific files: 
1.df = pd.read_csv('data/zippedData/imdb.title.basics.csv.gz
2.df2 = pd.read_csv('data/zippedData/imdb.title.ratings.csv.gz
3.df3 = pd.read_csv('data/zippedData/bom.movie_gross.csv.gz

They relate to the data analysis questions because all of them provide insight into what important strategies the company needs to look into and implement to make a successful movie or bring a successful movie to fruition. The data represents critical variables for analysis such as: primary title, average rating, num votes and gross income (domestic and international) that was receieved for each production. I believe the target variable can't be singled down to one as all are working together in some capactity to create a successful movie; however, I do believe average rating is the most important variable. As it is seen in analysis, that the movies with higher average rating made more money gross income overall and were the most profitable. Now, what aided the average rating has greatly to do with marketing and advertising and what movies are in the limelight for critics to reviews, and nevertheless are recommended to the audience more quickly than movies with lower ratings. The properties of the variables are 
***
Questions to consider:
* Where did the data come from, and how do they relate to the data analysis questions?
* What do the data represent? Who is in the sample and what variables are included?
* What is the target variable?
* What are the properties of the variables you intend to use?
***

## Methods

Describe the process for analyzing or modeling the data. For Phase 1, this will be descriptive analysis.

***
Questions to consider:
* How did you prepare, analyze or model the data?
* Why is this approach appropriate given the data and the business problem?
***

## Results

Present your key results. For Phase 1, this will be findings from your descriptive analysis.

***
Questions to consider:
* How do you interpret the results?
* How confident are you that your results would generalize beyond the data you have?
***

Here is an example of how to embed images from your sub-folder:

### Visual 1
![graph1](./images/viz1.png)

## Conclusions

Provide your conclusions about the work you've done, including any limitations or next steps.

***
Questions to consider:
* What would you recommend the business do as a result of this work?
* What are some reasons why your analysis might not fully solve the business problem?
* What else could you do in the future to improve this project?
***

## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact **name & email, name & email**

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
