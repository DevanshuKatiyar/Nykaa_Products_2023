```markdown
# Nykaa Product Analysis README

## About:

Welcome to the Nykaa Product Analysis project! This project aims to provide data analysts and researchers with insights into pricing strategies, product popularity, and customer preferences on the Nykaa platform.

The dataset includes several fields that offer valuable information about the products available on Nykaa. Here are the key fields available in the dataset:

- **Name**: Represents the name or title of the product, including the brand name, product name, and sometimes additional details like the variant or flavor.
- **Reviews**: Counts of reviews a product has received.
- **Offer Price**: Represents the reduced price of a product during a promotional period or when a specific offer/discount is applicable.
- **Original Price**: Provides the original or regular price of the product, without any offers or discounts applied.
- **Discount**: Specifies the percentage or amount of discount applied to the product, indicating the difference between the original price and the offer price, expressed as a percentage.
- **Free Gift**: Indicates whether a free gift is available or not.

## Work Done:

### Data Mining:
- Removed unwanted unnecessary strings such as parentheses from reviews, 'MRP:₹' from the original price, '₹' from the offer price, and '%' from the discount.
- Dropped null values from the dataset to ensure data quality.

### Exploratory Data Analysis (EDA):
- Conducted EDA to understand the relationships and distributions within the dataset.
- Explored correlations between original price and discount.
- Generated distribution plots for all numeric columns, focusing on the distribution of original prices.
- Added a categories column to specify product categories.

### Linear Regression:
- Utilized linear regression to predict a new column based on the dataset.

## Repository Structure:
- **data**: Contains the raw dataset and any processed data files.
- **notebooks**: Jupyter notebooks used for data preprocessing, EDA, modeling, and analysis.
- **results**: Results and outputs generated from the analysis, including visualizations and reports.

## Getting Started:
1. Clone this repository to your local machine.
2. Ensure you have Python 3.x installed along with necessary libraries (e.g., pandas, numpy, matplotlib, seaborn, scikit-learn).
3. Navigate to the `notebooks` directory and open the Jupyter notebooks to explore the analysis and results.
4. Follow along with the steps outlined in the notebooks to reproduce the analysis or modify it as needed.

## Contributing:
- Contributions to this project are welcome! Feel free to fork this repository, make changes, and submit pull requests.
- For major changes, please open an issue first to discuss proposed updates or improvements.

