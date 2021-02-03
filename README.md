# stackoverflow-2020

Table of Contents

    Installation
    Project Motivation
    File Descriptions
    Results
    Licensing, Authors, and Acknowledgements

Installation

This code only includes Numpy, Pandas, matplotlib, seaborn and scipy. These are all available from Anaconda, and was run on Python 3.

Project Motivation

Curiousity as to whether it is "too late" for those ages 20+ to begin their coding careers.

CRISP-DM Approach

Business understanding - there is a lot of talk about reskilling from different sectors of the economy 
to coding. I want to see if age alone as a factor matters in coders finding lucrative careers

Data Understanding - The survey data we have lists the age the respondents first started coding. We can use that as a measure to tell whether starting later makes a major effect on salary. This data is manually entered so it will need to be investigated and cleaned in order to draw any conclusions.

Data preparation - what we will need is to compare the age someone first started coding to their salary to do that we will need to make sure the values for salary and ages first coded are there. Luckily for us, the data includes a columns for salaries in US dollars so we will not have to do any converting of currencies

Modeling - We will use a simple scatter plot with a line of best fit to analyse the data

Evaluation - We will check the correlation coefficient to see how strong the correlation between the age you first code and your salary are

Deployment - We will generate easy readable graphs so stakeholders will be able to see the results.

File Descriptions

The Jupyter notebook of all my work in preparing the data and analysis. StackOverflow_2020_Code_Starts.ipynb

Results

You can find my write-up of my findings here: https://matthewedyoung.medium.com/age-is-just-a-data-point-250457788df8.

Licensing, Authors, Acknowledgements

Thank you to Udacity and Stack Overflow. This wouldn't be here without them.
