
# README - Group 18
## Presley Whitehead, Andrea Ritter, Matheus Santos Gomes, Joaquin Hidalgo-Estrada, Caio Rosa Rocha

### Inside the .zip
After extracting .zip, it should contain:  
    - README.md  
    - DataCollection&Analysis.ipynb  
    - Regression.ipynb  
    - vis.ipynb  
    - final_features.csv  
    - market_monthly.csv  
    - stocks_monthly.csv  
    - trends_monthly.csv  

**README.md** will guide\inform users on how to run notebooks, installation of required packages,  
source of dataset, and what each file inside .zip does.   
**DataCollection&Analysis.ipynb** will contain all the code used to create the datasets used in  
the visualizations.  
**Regression.ipynb** will show linear regression models that aim to predict excess returns.  
**vis.ipynb** will show data visualizations and data manipulation.  
**final_features.csv** contains a dataset with 40 features and 68 observations, where each feature  
describes one of the following AI related stocks:  
    - AMZN  
    - META  
    - GOOGL  
    - NVDA  
    - MSFT  
The types of descriptions are as follows:  
    - returns  
    - excess returns  
    - Google search trends scores  
Each observation corresponds to the first day of each month, ranging from January 2020 to October  
2025, when the project began.  
**market_monthly.csv** contains a dataset with 6 features and 70 observations, where each feature  
describes S&P500 in the following ways:  
    - Opening price  
    - Closing price  
    - Price high  
    - Price low  
    - Adjusted closing price  
    - Volume  
Each observation corresponds to the first day of each month, ranging from January 2020 to October  
2025, when the project began.  
**stocks_monthly.csv** contains a dataset with 70 observations, where the features are the same  
types of descriptions as market_monthly.csv, but are instead describing the same AI related stocks  
in final_features.csv.  
**trends_monthly.csv** contains a dataset with 10 features and 70 observations, where the features  
are AI related search terms, and each observation corresponds to the Google trends score for each  
search term on the first day of each month, ranging from January 2020 to October 2025.  

### Data Sources
All Google trends data is sourced from the [Google Trends website.](https://trends.google.com/trends/)  
All stock related data is sourced from the Yahoo Finance API.  

### Package Installation
Before running any code cells in any of the .ipynb files, install the required packages by running  
the following code in a Python environment:  
    `pip install package`  
Replace 'package' with each of the required packages:  
    - yfinance  
    - pandas  
    - matplotlib  
    - altair  
    - scipy  
    - statsmodels.api  
    - datetime  

### How to Run the .ipynb Files
    - For every .ipynb file included in the .zip, the user should run the code cells in the order  
    they appear.   
    - We found the visualizations did not load properly in Spyder, but did load in Jupyter Notebooks,  
    so we recommend that users open and run the files in a web-based environment, like Jupyter Notebooks.  
    - The majority of data visualizations will be found in vis.ipynb, however, some visualizations can  
    also be found in DataCollection&Analysis.ipynb.  