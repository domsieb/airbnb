# Dive into Munich Airbnb Data

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

- Install a recent version of python anaconda distribution
- Download the data from [here](https://www.kaggle.com/shoaibmnagi/munich-airbnb-listings-data-may-24-2020) and put it into the data folder
- Clone the repository and run all files

## Project Motivation<a name="motivation"></a>
In this project, I analyze the growth and the evoluation of the AirBnb business in Munich by using the currently available data to predict the prize of a listing. The following questions are to be answered by this notebook.

- Did the AirbnB business grow and evolve in Munich?
- What are the most popular neighboorhoods in Munich and what makes them popular?
- Can we predict a listing price and what are the most important features to estimate Airbnb rental price?

In order to analyze and evaluate the data we are employing the CRISP-DM process:

- Business Understanding - we have raised the three questions above about the Airbnb Business in Munich 
- Data Understanding - we have explored the three test sets provided by Kaggle/Airbnb
- Data Preparation - we have cleaned the data by dropping features, by imputing values, and by converting categorical into numerical data from the original data set
- Modelling - we have modelled the prediction question with a random forest regressor 
- Evaluation - we have evaluated the resuling model with the mean square error in the test set
- Deployment - we have discussed the findings as a final report in a medium blog post [here](https://dominiksieber.medium.com/how-did-airbnb-evolve-in-munich-8a2b73f83f5b).

## File Descriptions <a name="files"></a>

The  jupyter notebooks `airbnb_analysis_munich.ipynb` is available here in this repo to illustrate the required steps which were necessary to analyse the available data and to finally answer the above questions. 

The notebook also contains the function that generates the final model which is used to predict the listing price.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://dominiksieber.medium.com/how-did-airbnb-evolve-in-munich-8a2b73f83f5b).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/shoaibmnagi/munich-airbnb-listings-data-may-24-2020). Feel free to use the code here as you like.