# Diwali-_Market-_Data_analysis

This project analyzes Diwali sales data using Python and popular data science libraries like Pandas, NumPy, Matplotlib, and Seaborn.

## Data Source

The dataset used for this analysis is named "Diwali Sales Data.csv". It is assumed to be located in the `/content/` directory of the Colab environment.

## Data Cleaning

The following data cleaning steps were performed:

1. Unnecessary columns ('Status' and 'unnamed1') were dropped.
2. Rows with missing values were removed.
3. The 'Amount' column was converted to integer data type.

## Exploratory Data Analysis

The analysis focused on the following aspects of the data:

* **Gender:** Analyzed sales distribution by gender.
* **Age:** Explored sales trends across different age groups.
* **State:** Identified top-performing states in terms of sales.
* **Marital Status:** Compared sales between married and unmarried customers.
* **Occupation:** Investigated sales patterns based on customer occupation.
* **Product Category:** Determined the most popular product categories.
* **Product ID:** Identified the top-selling products.

## Visualization

The analysis utilized various visualizations, including count plots, bar plots, and grouped bar plots, to gain insights from the data. These visualizations were created using Seaborn and Matplotlib.

## Conclusion

The analysis revealed valuable insights into Diwali sales patterns, customer behavior, and product performance. These findings can be used to optimize marketing strategies, improve inventory management, and enhance customer targeting.

## Dependencies

This project requires the following Python libraries:

* pandas
* numpy
* matplotlib
* seaborn

These libraries can be installed using `pip`:
