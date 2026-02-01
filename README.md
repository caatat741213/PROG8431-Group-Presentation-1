# E-commerce Data Exploration & Statistical Analysis

## Project Overview
This project explores a e-commerce dataset to analyze pricing structures and discount distributions. By calculating key statistics like mean and standard deviation, we identify market trends. Visualizations, including scatter plots and Venn diagrams, help illustrate the relationship between product categories and customer purchasing behaviors.

## Research Question
* **Primary Inquiry**: How is product pricing distributed across the platform, and is there a discernible relationship between product prices and the discounts applied?

## Statistical Summary
Based on the analysis of 50,000 transaction records, the following key metrics were calculated for **Price (Rs.)**:

| Metric | Value |
| :--- | :--- |
| **Mean** | 254.80 |
| **Median** | 253.84 |
| **Mode** | 185.53 |
| **Variance** | 20073.97 |
| **Standard Deviation** | 141.68 |
| **Q1 (25%)** | 134.01 |
| **Q3 (75%)** | 377.60 |
| **Q4 (Max)** | 499.96 |

## Visualizations Explained
The following charts were implemented to provide a comprehensive view of the data:

1. **Histogram**: Visualizes the price distribution. The symmetric shape indicates that products are evenly spread across different price points.
2. **Box-whisker Plot**: Highlights the Interquartile Range (IQR) and confirms that there are no significant outliers in the dataset.

3. **Scatter Plot**: Explores the correlation between Price and Discount. The random distribution suggests that discounts are not strictly dependent on the item's price.
4. **Venn Diagram**: Analyzes the intersection between "High Price" (above median) and "High Discount" categories to visualize promotional trends.

## 50-Word Summary
This analysis investigates an e-commerce dataset containing 50,000 transactions. Statistical results show a symmetric distribution with a mean price of 254.80. Visualizations reveal that discounts are applied uniformly across all price ranges, as the scatter plot shows no strong correlation, and the Venn diagram illustrates a balanced overlap between high-priced and high-discount items.

## Setup and Installation
To run this project locally, please follow these steps:

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/caatat741213/PROG8431-Group-Presentation-1.git](https://github.com/caatat741213/PROG8431-Group-Presentation-1.git)
