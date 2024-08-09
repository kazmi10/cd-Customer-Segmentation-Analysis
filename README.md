# Customer Segmentation Analysis

## Overview
This project involves performing customer segmentation on a financial dataset using K-Means clustering. The goal is to identify distinct customer segments based on their credit card usage patterns, which can be used to inform targeted marketing strategies and improve risk management.

## Dataset
The dataset consists of 8,950 credit card customers with the following key features:
- **BALANCE:** The account balance of the customer.
- **PURCHASES:** The total amount of purchases made by the customer.
- **ONEOFF_PURCHASES:** The total amount of one-time purchases.
- **INSTALLMENTS_PURCHASES:** The total amount of installment purchases.
- **CASH_ADVANCE:** The total amount of cash advances taken by the customer.
- **CREDIT_LIMIT:** The credit limit of the customer.
- **PAYMENTS:** The total payments made by the customer.
- **MINIMUM_PAYMENTS:** The minimum payments made by the customer.
- **PRC_FULL_PAYMENT:** The ratio of payments to the full balance.
- **TENURE:** The number of months the customer has been a customer.

## Objective
The objective of this project is to segment customers into distinct groups based on their behavior and financial activities, enabling the identification of high-value customers, those reliant on cash advances, and more.

## Methodology
1. **Data Preprocessing:** 
   - Handled missing values in `CREDIT_LIMIT` and `MINIMUM_PAYMENTS` columns using the median.
   - Standardized the features to ensure consistency.
   
2. **Exploratory Data Analysis (EDA):**
   - Analyzed feature distributions and relationships using histograms and correlation matrices.
   
3. **Clustering:**
   - Used the Elbow Method to determine the optimal number of clusters.
   - Applied K-Means clustering to segment customers into 4 distinct groups.
   
4. **Cluster Analysis:**
   - Identified key characteristics of each cluster and provided actionable business insights.

## Results
- **Cluster 0:** Low-value, less engaged customers with low balances and spending.
- **Cluster 1:** Customers heavily reliant on cash advances.
- **Cluster 2:** High-value, highly engaged customers with high balances and spending.
- **Cluster 3:** Moderately engaged, financially responsible customers who often pay their balances in full.

## Insights & Recommendations
- **Cluster 2:** Target with premium offers and rewards programs.
- **Cluster 1:** Provide financial education and support to reduce reliance on cash advances.
- **Cluster 0 & 3:** Implement tailored engagement strategies to increase value and maintain financial responsibility.

## Tools Used
- **Python**
- **Pandas**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/kazmi10/Customer-Segmentation-Analysis.git
2. Navigate to the project directory:
   cd Customer-Segmentation-Analysis
3. Open the Jupyter Notebook/colab (Customer_Segmentation_Analysis.ipynb) in Jupyter or any other compatible environment.

Future Work
Explore advanced clustering techniques such as hierarchical clustering or DBSCAN.
Incorporate additional features like demographic data to refine segmentation.
Implement predictive modeling to forecast customer behavior.
Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements.

License
This project is licensed under the MIT License - see the LICENSE file for details.

### **Steps to Add the README to GitHub:**

1. **Create the README.md File:**
   - In your GitHub repository, click on "Add file" and select "Create new file."
   - Name the file `README.md`.

2. **Copy and Paste the Content:**
   - Copy the content of the README file provided above and paste it into the GitHub editor.

3. **Commit the File:**
   - Scroll down and click "Commit new file" to save the README.md to your repository.

### **Explanation:**
- **Overview:** Provides a summary of the project and its purpose.
- **Dataset:** Describes the dataset and key features.
- **Objective:** States the goals of the project.
- **Methodology:** Briefly explains the steps taken during the project.
- **Results:** Summarizes the findings from the clustering analysis.
- **Insights & Recommendations:** Provides actionable insights derived from the project.
- **Tools Used:** Lists the tools and technologies applied.
- **How to Run the Project:** Offers instructions for running the project locally.
- **Future Work:** Suggests potential enhancements and areas for further exploration.
- **Contributing:** Encourages others to contribute to the project.
- **License:** Indicates the project's license.

This README will make your project easy to understand and navigate for anyone visiting your repository.



