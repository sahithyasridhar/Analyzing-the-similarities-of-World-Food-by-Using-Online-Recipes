# NWSC-Project-SPR-2018 - "Analyzing the similarities of World Food by Using Online Recipes"
University of Indiana , Bloomington - 
Prajakta Patil , Nishad Tupe , Sahithya Sridhar 

Abstract :
People around the world are passionate about their food culture and they tend to think their food is most unique. Food and nutrition data provide an invaluable information about the culinary culture around the world and shows strong similarity between the taste preferences. Using a database of over 9000 recipes and more than 20 cuisines we analyze ingredients and their nutritional values and use this knowledge to assess the predictability of recipes from different cuisines. We also determine how the food of different countries far separated geographically are similar. By performing different analyses on the food data set of different countries, this project studies and shows similarities between the different food cultures by studying the top ingredients, and the common ingredients used in different cuisines and their nutritional values.

This repository contains Python Code , Datasets , Gephi Images. 

Bin description :
Final_project_code.ipypnb - Loads train and test .json datasets and use scikit learn algorithms for cuisine analysis.
Food_network_project.iypnb - Loads .net files and performs basic Network Analysis and matplotlib plots for Graphs.
Top_5_Cuisine_Nutrient_Analysis.ipynb – Loads the Top_5.xlsx and produces various matplotlib plots for nutrients.
Cuisine_Hypothesis.ipynb - Loads .net files and plots the distributions for degree assortativity coefficient for null an real models.
Raw_USDA_Ingredients_Analysis.ipynb – Loads the USDA standard ingredient dataset and produces matplotlib various plots.
Project_code - Same file final_project_code used as backup code.
Datasets description :
all_data.net , small.net – Pajek files (Graphs).
train.json - Train dataset
test.json - Test dataset
Top_5.xlsx(Custom Dataset) - Top 5 ingredients per cuisine with nutrient information
ABBREV.xlsx – USDA standard dataset with ingredient nutrient(USDA.gov)
Vegnonvegsmall.csv ,projectbigdata_csv.csv(Custom Dataset)- Veg/Non Veg classification serves input to Gephi.
