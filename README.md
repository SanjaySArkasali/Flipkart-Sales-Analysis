# Flipkart Sales Analysis (2023)

## Overview

This analysis aims to assess our brand's sales performance, focusing on the impact of promotions and discounts. We'll also explore product returns, organic sales, and popular products by region. Additionally, we'll examine sales trends by time and day of the week. These insights will inform marketing strategies and product development for improved business outcomes.

## Table of Contents

- Data
- Analysis
- Results (Screenshots)

## Data

- The data for this analysis has been sourced from the Flipkart seller website.
- We have collected two essential datasets from Flipkart:
> - The first dataset is extracted from "Reports" -> "Tax Reports" -> "Sales Reports."
> - The second dataset is obtained from "Reports" -> "Fulfillment Reports" -> "Orders Report."
- The reason for utilizing these two datasets is twofold:
> - The Sales Report lacks order timestamps necessary for time-based trend analysis, which is critical for campaign optimization.
> - The Orders Report lacks information on invoice amounts and other crucial sales-related data.

## Analysis

- Import the datasets and concat the datasets into one seperately sales, orders(because you'll have to download data month wise, and drop unnnecessary columns)
- Now merge the dataset orders on sales 'left' join on common column 'order_id' (foramt the order id columns name and content)
- Now just based on the event type and event sub type classify in to organic, promotinal and return columns.
- from the new date from order that is merged now extract hour
- Some rows have nulls in some columns which will support in other analysis thats why i haven't droped those rows.

[Power Bi dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzRiZjk5MzYtZGI0OC00MDkzLTk4MjMtODc4NTZlNDQ4MTMzIiwidCI6ImJmNDE4ZmE0LWM3NzQtNDViMS05YWZiLTM0NjgyNGVlYWZlMSIsImMiOjEwfQ%3D%3D)
## Results (Screenshots)
![project 2 scrennshot1](https://github.com/SanjaySArkasali/Flipkart-Sales-Analysis/assets/121194268/c4b12fdb-2f79-4ed6-b5de-9990bbd140c6)
![screenshot3](https://github.com/SanjaySArkasali/Flipkart-Sales-Analysis/assets/121194268/3d6c6962-ff05-4bce-b052-0ba7e7ffcd9e)
![screenshot2](https://github.com/SanjaySArkasali/Flipkart-Sales-Analysis/assets/121194268/0cb0cb5f-0b07-4078-82be-f2a8acdfe36f)

