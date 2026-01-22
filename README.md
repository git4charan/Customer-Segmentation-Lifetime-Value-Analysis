# Customer Segmentation & Lifetime Value Analysis

## Overview
This project analyzes e-commerce transactional data to segment customers based on purchasing behavior and estimate customer lifetime value (LTV).  
The analysis is designed to support data-driven marketing, retention, and prioritization strategies.

## Objectives
- Perform RFM (Recency, Frequency, Monetary) analysis
- Segment customers using K-Means clustering
- Identify high-value and at-risk customer segments
- Prepare clean analytical outputs for Power BI visualization

## Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook
- Power BI
- GitHub

## Methodology
1. Data cleaning and preprocessing of transactional data
2. Customer-level RFM feature engineering
3. Feature transformation and scaling
4. K-Means clustering for customer segmentation
5. Business interpretation of customer segments
6. Export of final datasets for visualization

## Key Insights
- A small segment of customers contributes disproportionately to overall revenue
- Clear distinction between loyal, potential, and at-risk customers
- Segmentation enables targeted retention and reactivation strategies

## Power BI Dashboard
Interactive visualizations were created to explore customer segments:
- Treemap of revenue contribution by segment
- Scatter plot of Frequency vs Monetary value
- Segment-level summary tables

Screenshots are available in the `powerbi/` directory.

## Repository Structure
Customer-Segmentation-LTV/
├── data/
├── notebooks/
├── outputs/
├── powerbi/
└── README.md



## How to Run
1. Clone the repository
2. Install required Python libraries
3. Open `notebooks/customer_segmentation_ltv.ipynb`
4. Run cells sequentially
5. Open `powerbi/customer_segmentation_dashboard.pbix` to explore visuals

## Future Improvements
- Advanced LTV modeling
- Time-based cohort analysis
- Automated reporting pipeline
