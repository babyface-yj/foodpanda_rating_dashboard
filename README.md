# Foodpanda Rating Dashboard

Summary: the raw data has all resturants in Foodpanda with name, rating, reviewers, food type, while location information is minimum and it's part of the store name, the purpose of this project is to create dashboards 1st to have summary to show different food type ratings and popularities with Geo info to see store distributions. 2nd to have filter function to filter all different store using either rating, food type or location etc.

This is a Tableau Dashboard project (https://public.tableau.com/app/profile/yongjian.huang/viz/FoodpandaResturantRating/Foodsummary)

Data source: https://www.kaggle.com/datasets/bwandowando/food-panda-resto-reviews

Data cleansing and preparation steps (data_cleaning.ipynb)
- remove unrelevant columns
- remove the unrelevant entries
- change to relevant data type
- add location and geo info using geopy
