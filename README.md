# MobileUp - Price suggestion tool to optimize sales pitch
This project focuses on using raw data and solving niche problem of price suggestion for used iPhone mobiles. For this project we have followed CRISP-DM process.

# CRISP-DM Process:

<img src="https://github.com/ShrideviReddy/MobileUp/blob/main/img/CRISP_DM.png" width="400" height="200">

# Business understanding:
![Pricediff](img/Pricediff.PNG)

We want to build an algorithm that automatically suggests the right product prices from the user-inputted listing title of their products and help seller to make his/her
product stand-out. 
* The goal is to solve the problem of suggesting the appropriate price of products to online sellers.
* No latency constraints, because we would like to suggest a highly accurate price to the seller, even if it takes a reasonable amount of time.

# Our Solution:
* Creating app which gives iPhone sellers estimate of Price based on listing title.
* Together with interpretation of price, it also highlights important keywords they can include to optimize listing and get better price.

# Data Source:
![Datasrc](img/Datasrc.PNG)

You can check code for eBay scraping here.

# Data Pipeline:
![Datapipeline](img/Datapipeline.PNG)

For feature engineering :
* Used Pandas Data manipulation tools to create and extract relevant features from listing title.
* Treating outliers and missing values if any.

# Model Category Matters (ofcourse!):
![Modelprice](img/modelvsprice.PNG)

# Modelling:
![Modelling](img/Modelling.PNG)




