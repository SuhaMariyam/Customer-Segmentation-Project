# Customer-Segmentation-Project
# Customer Segmentation: Gaining Actionable Insights

## Project Overview
Understanding customer behavior is crucial for business growth. In this project, we applied clustering techniques to segment customers effectively, revealing distinct groups and valuable insights.

## Our Approach
✅ **Data Preprocessing & EDA** – Cleaning and exploring patterns.

✅ **K-Means & Hierarchical Clustering** – Using the **Elbow Method** & **Dendrogram** to determine the optimal number of clusters (**k=2**).

✅ **Final K-Means Model (k=2)** – Grouping customers based on spending patterns, age, and discounts.

## Key Insights from Clustering
📌 **Cluster 0** – Younger customers (~29 years old), higher spending ($783.25), slightly higher quantity per purchase.

📌 **Cluster 1** – Older customers (~53 years old), slightly lower spending ($765.08), but a similar discount rate.

This segmentation can help businesses tailor their **pricing strategies, promotions, and product recommendations** to different customer groups.

## Dataset
- **Source**: www.kaggle.com
- **Features**:
  -Transaction ID
  -Product ID
  -Product Name
  -Category
  -Price
  -Quantity Sold
  -Customer Age
  -Customer Gender
  -Transaction Date
  -Payment Method
  -Discount	-Region
  -Membership Status
![image](https://github.com/user-attachments/assets/b48111d8-98ca-49a5-b757-9e0ffaa55c0b)

## Tools & Technologies
- **Programming Language**: Python
- **Libraries Used**:
  - Pandas, NumPy (Data Processing)
  - Matplotlib, Seaborn (Data Visualization)
  - Scikit-learn (Machine Learning - Clustering)
  - Plotly (Interactive Visualizations)

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-segmentation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd customer-segmentation
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook
   ```


