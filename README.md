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
![image](https://user-images.githubusercontent.com/56518821/111862100-61a80d80-8929-11eb-9cf2-272560531946.png)

![image](https://user-images.githubusercontent.com/56518821/111862092-5359f180-8929-11eb-8740-9336dbce947a.png)
![image](https://user-images.githubusercontent.com/56518821/111862093-55bc4b80-8929-11eb-8e03-ace9ec9274b3.png)

![image](https://user-images.githubusercontent.com/56518821/111862056-1a218180-8929-11eb-9d7b-f33be0b72283.png)
![image](https://user-images.githubusercontent.com/56518821/111862075-345b5f80-8929-11eb-83a4-ebd28937c569.png)








