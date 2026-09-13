# Airbnb NYC — Exploratory Data Analysis

Exploratory Data Analysis of the **New York City Airbnb Open Data** dataset to understand pricing patterns, room types, neighbourhoods, reviews, and availability.

## Dataset

**New York City Airbnb Open Data** — Kaggle

* **Rows:** 48,895
* **Columns:** 16
* **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data/data)

## Analysis

* Data understanding and cleaning
* Price and minimum nights distributions
* Listings by neighbourhood group and room type
* Median price by room type and neighbourhood group
* Reviews and availability vs. price
* Neighbourhood × room type interaction
* Correlation analysis

## Key Findings

* Manhattan and Brooklyn have the most listings.
* Entire home/apt has the highest median price.
* Manhattan has the highest median listing price.
* Price, minimum nights, and number of reviews are highly right-skewed.
* Room type and neighbourhood group show clear relationships with price.
* `number_of_reviews` and `reviews_per_month` have the strongest correlation (**0.59**).

## Tools

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Project Structure

```text
Airbnb-NYC-EDA/
│
├── Airbnb_NYC_EDA.ipynb
├── README.md
└── AB_NYC_2019.csv
```

## Conclusion

The analysis reveals clear pricing differences across room types and NYC neighbourhoods, while most numerical variables have relatively weak linear relationships. These findings provide a foundation for further analysis and price-prediction modeling.
