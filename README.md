BigBasket Products Analysis with Power BI

Project Overview

This project aims to analyze and visualize a dataset of BigBasket products using Power BI. The dataset includes information 
about product categories, sub-categories, sale prices, ratings, and other attributes. The goal is to create an insightful 
dashboard that provides a clear view of product distributions, pricing trends, and customer ratings.

Dataset

The dataset is provided as a CSV file named BigBasket Products.csv and contains the following columns:

- category: The main category of the product.
- sub_category: The sub-category of the product.
- product: The name of the product.
- sale_price: The sale price of the product.
- rating: The customer rating of the product.

Visualizations

1. Category Distribution
2. Sub-Category Distribution within Each Category
3. Average Sale Price per Sub-Category
4. Total Number of Products per Category
5. Number of Products with Ratings Above 4
6. Products Priced Above Average in Each Category
7. Most Popular Product in Each Category Based on Highest Average Rating

Project Structure

.
├── BigBasket Products.csv
├── SQL Server
└── PowerBI
    ├── BigBasketDashboard.pbix
    └── visuals
        ├── category_distribution.pie
        ├── sub_category_distribution.treemap
        ├── avg_sale_price_per_sub_category.bar
        ├── total_products_per_category.column
        ├── high_rated_products.card
        ├── products_priced_above_avg.scatter
        └── most_popular_product.table


