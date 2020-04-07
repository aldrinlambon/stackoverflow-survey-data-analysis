# Stackoverflow Survey Data Analysis

## Project Motivation
For this project, I was interested in better understanding the characteristics of freelance developers, specifically:
1. Which countries do freelance developers mostly reside?
2. What types of developers do freelancing?
3. How does skill sets and job satisfaction relate to salary as a freelancer?

## Data Source
The data that was used in the project is the Stack Overflow survey data from 2017-2019 this was retrieved from https://insights.stackoverflow.com/survey, where the data is licenced under Open Database License (ODbL).

## Data Preparation
Considering the motication and the questions we want to answer, I have selected the following variables for the analysis:

*EmploymentStatus*
- This variable was used to select the rows where the type of employment is independent, contract or freelance

*Country*
- This variable will help us identify countries where most freelance developers resides.

*DeveloperType, Languages, Databases, Platforms, and Web Frameworks*
- These variables serves as basis to understand what are the skillsets a freelance developer have. The following variables can also help use which type of work is more frequent for freelance developers.

*Salary*
- This variable will be used in the modeling selection of the analysis and help us identify variable that can be indicators of higher overall salary

## Salary Modeling
By creating a model to predict salary we can also identify variables and characteristics that can lead to a higher overall salary. The modeling steps are as follows:

- Create a trainset and testset
- Perform One hot encoding to the categorical variables
- Initialize and fit a Linear Regression model
- Evaluate the model coefficients

## Results

The main findings of the analysis and modeling can be found at this blog post
[link](https://medium.com/@aldrinl/freelance-developers-worldwide-b06f344720af)
