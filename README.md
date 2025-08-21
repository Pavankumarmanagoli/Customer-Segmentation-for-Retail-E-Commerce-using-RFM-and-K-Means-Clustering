
# 🛒 Customer Segmentation for Retail E-Commerce using RFM and K-Means Clustering

This repository demonstrates an end-to-end workflow for segmenting customers of an online retail business. The analysis cleans and explores transactional data, derives Recency, Frequency and Monetary (RFM) features, and applies K-Means clustering to uncover actionable customer groups.

## Project Objective
Gain a deep understanding of how different customers behave so marketing spend can be focused where it has the greatest impact.
The analysis transforms raw transaction logs into RFM scores and uses K-Means clustering to:

- Uncover purchasing patterns hidden in the data.
- Highlight high-value customers who warrant retention efforts.
- Flag disengaged shoppers that may be drifting toward churn.
- Inform personalized promotions and product recommendations.

By tailoring outreach to the needs of each segment, retailers can improve customer lifetime value, reduce unnecessary discounts, and build stronger long-term relationships.

## Getting Started
### Clone the repository
```bash
git clone https://github.com/Pavankumarmanagoli/Customer-Segmentation-for-Retail-E-Commerce-using-RFM-and-K-Means-Clustering.git
cd Customer-Segmentation-for-Retail-E-Commerce-using-RFM-and-K-Means-Clustering
```

### Install dependencies
This project requires Python 3 and the following packages:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn scipy
```

### Run the notebook
Open the notebook locally or in Google Colab to reproduce the analysis:

```bash
jupyter notebook E-commerce.ipynb
```

## Methodology
1. **Data Preparation** – handle missing values and outliers.
2. **Exploratory Data Analysis** – visualize purchasing trends.
3. **RFM Calculation** – compute recency, frequency and monetary value for each customer.
4. **K-Means Clustering** – group customers using RFM features with silhouette analysis to select the cluster count.
5. **Insights** – interpret clusters and provide marketing recommendations.

## Results
The analysis yields three main segments:

- **Loyal Customers** – high spending and recent activity. Maintain engagement through loyalty programs.
- **Potentially Churned** – moderate spend but long time since last purchase. Re-engage with targeted promotions.
- **Casual Shoppers** – low spend and moderate recency. Encourage repeat purchases with vouchers or cashback.

## Repository Structure
- `E-commerce.ipynb` – Jupyter notebook containing the full analysis.

## Acknowledgements
Data inspiration from the Olist e-commerce dataset and community notebooks.

## License
This project is licensed under the [MIT License](LICENSE).
