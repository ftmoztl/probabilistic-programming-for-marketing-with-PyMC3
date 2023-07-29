# Probabilistic Programming for Marketing with PyMC3
This repository proposes a probabilistic programming approach to predict the success rate of telemarketing calls for long-term bank deposits. 

Generalized Linear Models and Multilevel Models approaches were used to create a scientific model and to analyze potential client who subscribes to a long-term deposit, which is considered an output variable. The causal relationship between marketing attributes and outcomes was created and interpreted according to the model results.

In this study, the probabilistic programming models are used by using the Python Pymc3 library to analyze the factors which have an effect on a potential client's subscription to a long-term deposit. You can find a detailed explanation of this study in this paper.

# Dataset
The ‘bank-additional’ dataset of the "Bank Marketing Dataset" was used to analyze the effect of different variables in the marketing area. The bank dataset includes 10 numeric attributes and 11 categorical attributes. 

# Environment
To install the dependencies to run the notebook, you can use Anaconda. Once you have installed Anaconda, run:

`$ conda env create -f environment.yml`

# Notebook 
This Jupyter Notebook includes all code used for this study. It includes the following sections;
* Explanations of dataset attributes
* Exploratory Data Analysis
* Problem Definition
* Creation of Causal Graph (DAG) with Assumptions
* Data Transformation
* Creation of scientific models with different attributes by using PYMC3
* Additional Studies for analyzing the effect of different attributes on the target.


# Proposed Resources

[Statistical Rethinking][id/name]  is a proposed book for understanding the essentials of Bayesian Statistics, which introduces the probabilistic approach to the general problems solved by frequentist statistics. This study was utilized from this book.

[id/name]: http://xcelab.net/rm/statistical-rethinking/

Other related studies:
* Moro, S., Cortez, P., & Rita, P. (2014). A data-driven approach to predict the success of bank telemarketing. Decision Support Systems, 62, 22-31.
* Reilly, G. O. (2005). Information in financial market indicators: an overview. Quarterly Bulletin Articles, 4, 133-141.
* Mehrotra, A., & Agarwal, R. (2009). Classifying customers on the basis of their attitudes towards telemarketing. Journal of Targeting, Measurement and analysis for Marketing, 17(3), 171-193.
* Hosseini, S. (2021). A decision support system based on machined learned Bayesian network for predicting successful direct sales marketing. Journal of Management Analytics, 8(2), 295-315.

# Contribution
If you want to contribute please, send your pull request. All contributions are welcome!

#
Please check that repository for updates, for opening issues, or sending pull requests.
