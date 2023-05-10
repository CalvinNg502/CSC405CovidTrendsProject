# CSC405-01TeamCCKProject

## Table of Contents
* [Introduction](#introduction)
* [Technologies](#technologies)
* [Launch](#launch)
* [Features](#features)
* [Status](#status)

## Introduction

This is the project repository for Team CCK's CSC405 project. Group members include Calvin Ng, Cole Yonkers, and Kachif Adefalou for parts I and II and include Calvin Ng and Cole Yonkers for Parts I through V. The purpose of this project is to analyze datasets through the use of python and data science packages in order to provide insight into COVID-19 trends.

The organization of this repository is simple. There is the Data directory, and there are the individual parts directories. Data contains all of our datasets, both base sets and those we've merged through python. Parts directories (Part I, Part II, etc) contains the group and individual jupyter notebooks along with pdfs of these notebooks for each stage of the project.

As mentioned in this repository's description, this is **NOT** the original repository! The original became bloated with extremely large files due to merging .csv files and getting an exponentially large .csv file in return. We have attempted to clean the repository, but have been unsuccessful, so we have resorted to deleting it and creating this repository. The most recent version of our work has been properly preserved, but unfortunately, the commit history has not, so it is impossible to discern which parts were written by what person. In general, each person was responsible for their own individual notebook, and the group notebooks were worked on as a team. This project was worked on from January, 2023, to April, 2023.

## Technologies

- dash 2.9.3
- matplotlib 3.5.2
- numpy 1.21.5
- pandas 1.4.4
- plotly 5.9.0
- Python 3.9.13
- scipy 1.9.1
- statsmodels 0.13.2

## Launch

To launch/use this project, you will need some way of opening a jupyter notebook. Our preferred method is Anaconda as it comes installed with many (but not all!) packages that you will need, but Anaconda is not requirred; any other python runtime environment will also suffice. 

You will also need to have all the packages listed above installed, too. Different versions of these packages may function properly, but be aware that some features this project uses might not exist in different versions, especially past versions. 

From within the notebook, run the cell(s) to execute the code they contain. It is recommended you run all the cells as some rely upon others to function. 

**It is utterly crucial that you run the group notebook, then each individual notebook in the Part I directory to create the merged .csv files. Every other stage attempts to read these files into dataframes, so if they do not exist, then those notebooks will not compile!**

## Features
- Merge related datasets together and perform preliminary analysis.
- Analyze the second half of 2022 cases and deaths and compare across nations, states, and counties.
- Create distribution estimators for different states.
- Calculate correlation between new cases and enrichment variables.
- Create linear and polynomial models for states and counties and use these models to create forecasts.
- Create hypotheses and test these hypotheses.
- Display data and models for different states in an interactive dashboard.

### To Do:
- Up to date.
## Status
- This project is officially complete! Expect there to be few to no changes to project files in the foreseeable future.
