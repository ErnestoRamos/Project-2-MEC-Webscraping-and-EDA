# MEC Webscraping and EDA Analysis: Price and Review Comparison 
- Wanted to identify how competitively priced and rated MEC products were relative to other brands sold in store 
- Scraped over 1500+ products from MEC website between Oct 25 - 27, 2020 using Beautiful Soup
- Collected categories include men's and women's clothing, footwear, camping equipment, snow equipment, watersports, and hiking 
  - for each item we retrieved: item name, brand, MSP, avg review, num of reivews, sale % (if any), saleprice (if any), product description.
- Main analyses include percent of products sold across all clothing as well as price of MEC products (relative to competitor brands sold in store) by avg product rating for men and women. 
- Additional analyses include percent of Top 5 brands vs total products for camping/hiking and dsitribution of product prices per brand for camping/hiking.  

# Code and Resources Used
Python Version: 3.8
Packages: numpy, pandas, Beautiful soup, requests, time, pandas, json, matplotlib, plotly, seaborn


# EDA
- A sample of some of the EDA performed on collected data to investigate pricing and review of MEC products relative to competitors in same category.  
![image](https://user-images.githubusercontent.com/56518821/111862034-f78f6880-8928-11eb-8011-e1eb3b0b5c74.png)
![image](https://user-images.githubusercontent.com/56518821/111861735-f2311e80-8926-11eb-89d0-2aaf0d0c5792.png)
![image](https://user-images.githubusercontent.com/56518821/111861739-f8bf9600-8926-11eb-8de8-7901037c2c66.png)
![image](https://user-images.githubusercontent.com/56518821/111862037-037b2a80-8929-11eb-870c-4fca23ed2942.png)
![image](https://user-images.githubusercontent.com/56518821/111862044-0b3acf00-8929-11eb-88df-c1df65875469.png)





