# Customer Segmentation Using Python

## Internship
**Organization:** Algonive  
**Domain:** Data Analytics  
**Project:** Customer Segmentation Using Python

## Project Overview
This project uses customer data to identify groups of customers with similar annual income and spending behavior. K-Means clustering is used to support customer segmentation and help businesses understand customer patterns.

## Objectives
- Analyze customer demographics and spending behavior.
- Clean and explore the dataset.
- Apply K-Means clustering to group customers.
- Visualize customer segments.
- Generate business insights from the results.

## Dataset
The Mall Customers dataset contains 200 customer records and the following columns:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Tools and Technologies
- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow
1. Load the dataset.
2. Check missing values and duplicate records.
3. Perform exploratory data analysis (EDA).
4. Visualize income and spending distributions.
5. Scale annual income and spending score features.
6. Use the Elbow Method to examine the number of clusters.
7. Apply K-Means clustering.
8. Visualize customer groups and summarize their characteristics.
9. Export the segmented dataset to CSV.

## Visualizations
- Customer distribution by gender
- Annual income distribution
- Spending score distribution
- Income versus spending score scatter plot
- Elbow Method plot
- K-Means customer segmentation plot
- Average spending score by cluster

## Results
The model assigns each customer to one of five clusters. The cluster summary compares customer counts, average age, annual income, and spending score.

The analysis can help businesses explore customer groups and consider targeted marketing strategies.

## Project Files
- `Customer_Segmentation_Algonive.ipynb` — notebook containing the code and analysis.
- `Customer_Segmentation_Results.csv` — customer records with cluster assignments and segment labels.

## How to Run
1. Download the notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the notebook and the required CSV file.
4. Run the notebook cells in order.

## Conclusion
This project demonstrates how data analysis, visualization, and K-Means clustering can be used to explore customer purchasing patterns and support business decisions.
