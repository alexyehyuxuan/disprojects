# Executive Summary

A city in central Iowa, United States, Ames hosts a population of 65,000 residents. Best known for being the home of the Iowa State University(ISU), Ames was also ranked ninth on a (["Best Places to Live"](https://money.cnn.com/magazines/moneymag/bplive/2010/snapshots/PL1901855.html)) list. For people looking to root in Iowa, a property doubles as a home as well as an investment. When people pick out homes, or do renovations, it's entirely possible to lose out on the investment by overpaying for bad property, or by making bad decisions during renovations. 

# Problem Statement
This project aims to find the answer for `which variables predict the valuation of property` in Ames, Iowa for new homeowners to better understand how property valuation works.

This project aims to solve this problem by utilizing regression models to determine the features that can influence the price of property in Ames and to which extent these features predict the prices. <br/> Divided into two Jupyer Notebooks: The first in which I clean the data, and the second where I plot out the data and fit it to models to isolate and define the extent of variables & their interconnected relationships in determining the price of the property. 

# Data Dictionary
The Data Dictionary can be found ([here](https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge/data))

# The Process
The data was first cleaned of nulls using educated guesses about the other data. Ordinal data was transformed into numerical, and categorical data was transformed into numerical via one hot encoding. 

Graphs were plotted to understand the data further, and once satisfied, the data was put into linear, ridge and lasso models and scaled to understand the fitting of the models to the data. Eventually, the remainding data was lassoed with a high alpha in order to cut down variables in order to obtain polynomial features which were lassoed to give the predictor that was eventually used for the kaggle submission. 


# Conclusions and Recommendations

As a new homeowner, it may be tough to isolate what parts of property to lookout for in order to make the best of your investment. With these variables, hopefully this can give people more confidence to make their best guess.

The biggest correlation for a house to sale price is unsurprisingly, the overall quality of the house, tied to the general living area. Additionally, the 2nd highest coef also alludes to the same thing. If a house is big and nice, it's gonna be costly.
Secondly, in most of the other relations, bsmtqual(The height of the basement) & lotarea for example, spaciousness drives prices.
It may be more prudent for homeowners to refrain from modifying the height of their basement since it could adversely affect the price of their home.
For people buying property in neighborhood_nright(Northridge Heights) having a significant amount of masonry veneer is valued. A stone wall is valued styling in that area.