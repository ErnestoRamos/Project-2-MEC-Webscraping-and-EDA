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
![image](https://user-images.githubusercontent.com/56518821/111861729-e9404d00-8926-11eb-98aa-6228f88f693b.png)
![image](https://user-images.githubusercontent.com/56518821/111861735-f2311e80-8926-11eb-89d0-2aaf0d0c5792.png)
![image](https://user-images.githubusercontent.com/56518821/111861739-f8bf9600-8926-11eb-8de8-7901037c2c66.png)
![image](https://user-images.githubusercontent.com/56518821/111861830-9ca94180-8927-11eb-8831-3ac813031d9a.png)
![image](https://user-images.githubusercontent.com/56518821/111861834-a03cc880-8927-11eb-9809-cbefeef99ebe.png)




