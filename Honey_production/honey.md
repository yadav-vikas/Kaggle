# Honey production in USA

The National Agricultural Statistics Service (NASS) is the primary data reporting body for the US Department of Agriculture (USDA).
NASS's mission is to "provide timely, accurate, and useful statistics in service to U.S. agriculture". 
From datasets to census surveys, their data covers virtually all aspects of U.S. agriculture. Honey production is one of the datasets offered. 
Click here for the original page containing the data along with related datasets such as Honey Bee Colonies and Cost of Pollination.
Data wrangling was performed in order to clean the dataset. honeyproduction.csv is the final tidy dataset suitable for analysis. 
The three other datasets (which include "honeyraw" in the title) are the original raw data downloaded from the site. 
They are uploaded to this page along with the "Wrangling The Honey Production Dataset" kernel as an example to show users how data can be wrangled into a cleaner format.
Useful metadata on certain variables of the honeyproduction dataset is provided below:

numcol: Number of honey producing colonies. Honey producing colonies are the maximum number of colonies from which honey was taken during the year. 
        It is possible to take honey from colonies which did not survive the entire year
yieldpercol: Honey yield per colony. Unit is pounds

totalprod: Total production (numcol x yieldpercol). Unit is pounds

stocks: Refers to stocks held by producers. Unit is pounds

priceperlb: Refers to average price per pound based on expanded sales. Unit is dollars.

prodvalue: Value of production (totalprod x priceperlb). Unit is dollars.

Other useful information: Certain states are excluded every year (ex. CT) to avoid disclosing data for individual operations. Due to rounding, 
total colonies multiplied by total yield may not equal production. Also, summation of states will not equal U.S. level value of production.
