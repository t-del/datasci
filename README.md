# Data Science / Machine Learning portfolio by Tom deLaubenfels

This portfolio is a compilation of notebooks/code which I created in order to explore data analysis and machine learning concepts. 


## Kaggle competitions

### Titanic: Machine Learning from Disaster

[titanic_ml.ipynb](https://github.com/t-del/datasci/blob/master/code/titanic_ml.ipynb)

[Kaggle page](https://www.kaggle.com/c/titanic)

In this competition we attempt to predict whether or not a subset of passengers on the Titanic survived the sinking. This is a classification problem with a relatively straightforward data set. By making several informed and intuitive transformations of the data, we can use a Random Forest classifier to achieve a score in the top 15%. 

### House Prices: Advanced Regression Techniques

[housing_prices_v1](https://github.com/t-del/datasci/blob/master/code/housing_prices_v1.ipynb)

[Kaggle page](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

This is a regression problem in which we attempt to predict house prices based on a variety of data about them. My work on this problem is underway as of November 2017.


## Personal projects

### Destiny 2 vendor tracker data

[D2_vendors_data_scraper.py](https://github.com/t-del/datasci/blob/master/code/D2_vendors_data_scraper.py)

The online video game Destiny 2 has various "vendors" which distribute equipment rewards to players. The equipment power levels fluctuate between the maximum possible and some level below maximum. The website http://destiny-vendor-gear-tracker.com/ was born as a community-reporting tool for keeping track of when (within 30 minute intervals) vendors were distributing the most powerful gear.

I built a web scraper to pull the historical logs from this website, with the intention of discovering any patterns which may exist in the vendor distributions. However, discussions within the game community, as well as some immediate looks at the data, strongly suggest that the distributions are simply random. In this end, this was simply a nice exercise in web scraping.
