# Assignment 1 (Clustering): TTE
## Instructions
New and novel methods in Machine Learning are made either by borrowing formulas and concepts from other scientific fields and redefining it based on new sets of assumptions, or by adding an extra step to an already existing framework of methodology.

In this exercise (Assignment 1 of the Clustering Topic), we will try to develop a novel method of Target Trial Emulation by integrating concepts of Clustering into the already existing framework. Target Trial Emulation is a new methodological framework in epidemiology which tries to account for the biases in old and traditional designs.

These are the instructions:
1. Look at this website: https://rpubs.com/alanyang0924/TTE
2. Extract the dummy data in the package and save it as "data_censored.csv"
2. Convert the R codes into Python Codes (use Jupyter Notebook), replicate the results using your python code.
3. Create another copy of your Python Codes, name it TTE-v2 (use Jupyter Notebook).
4. Using TTE-v2, think of a creative way on where you would integrate a clustering mechanism, understand each step carefully and decide at which step a clustering method can be implemented. Generate insights from your results.
5. Do this by pair, preferably your thesis partner.
6. Push to your github repository.
7. Deadline is 2 weeks from today: February 28, 2025 at 11:59 pm. (moved to Sunday March 9, 2025)

HINT: For those who dont have a thesis topic yet, you can actually develop a thesis topic out of this assignment.
I  dont mind you use A.I. tools with this assignment, but if you do please include your prompts in the submission.

## TTE Introduction

In this notebook, we convert the R implementation of Target Trial Emulation from https://rpubs.com/alanyang0924/TTE into python, and replicate the results using the python code. We already extracted the dummy data (data_censored.csv) from the TrialEmulation package in R, and we will be using that to replicate the results in the original R code of TTE.


## TTE-v2: Integrating Clustering Introduction
In this study, we incorporated **K-Means clustering before running Target Trial Emulation (TTE)** to address potential biases inherent in observational data. In real-world settings, treatment assignment is often **non-random** and influenced by underlying patient characteristics. Clustering provides a structured approach to stratifying the population into more homogeneous subgroups before estimating treatment effects.

