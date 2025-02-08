# Quantium-Retail-Analysis

## Overview

This project analyzes retail transaction data to uncover insights into customer behavior, sales trends, and trial store performance. The analysis follows a structured approach to data cleaning, feature extraction, and statistical comparisons to inform business decisions.

## Datasets

The datasets used in this project contain transactional data from multiple retail stores. They include:

1. **QVI Transaction Data** - Contains sales transaction records, including:

   - `DATE`: Transaction date
   - `STORE_NBR`: Store number
   - `LYLTY_CARD_NBR`: Customer loyalty card number
   - `TXN_ID`: Transaction ID
   - `PROD_NBR`: Product number
   - `PROD_NAME`: Product name
   - `PROD_QTY`: Quantity purchased
   - `TOT_SALES`: Total sales amount

2. **QVI Purchase Behavior Data** - Includes customer segmentation details:

   - `LYLTY_CARD_NBR`: Customer loyalty card number
   - `LIFESTAGE`: Customer life stage (e.g., Young Singles/Couples, Older Families, etc.)
   - `PREMIUM_CUSTOMER`: Customer category (Premium, Mainstream, Budget)

## Steps Performed

### **Task 1: Data Exploration & Cleaning**

- Loaded transaction data and performed **high-level data checks**.
- Identified and removed **outliers** to ensure data integrity.
- Derived additional features such as **pack size** and **brand name**.
- Analyzed customer segments to understand **spending behavior**.

### **Task 2: Store Performance Analysis**

- Evaluated monthly sales trends using:
  - **Total Sales Revenue**
  - **Total Number of Customers**
  - **Average Transactions per Customer**
- Selected control stores using **Pearson correlation & distance metrics**.
- Compared **trial vs. control stores** to assess sales impact.
- Conducted **t-tests** to determine statistical significance of changes.

## Key Findings

- **Top-Selling Product:** Kettle Mozzarella Basil & Pesto 175g.
- **Spending Trends:**
  - Affluent customers prefer **premium products**.
  - Budget-conscious customers prefer **mainstream brands**.
- **Trial Store Impact:**
  - Significant **sales increase** in trial stores.
  - Increase driven by **more unique customers**, not higher transaction frequency.

## Usage Instructions

1. Open the **Jupyter Notebooks** (`.ipynb` files) for detailed analysis.
2. Run the notebooks sequentially to replicate data cleaning, exploration, and insights.
3. Use visualizations in the notebooks to interpret key trends.

This README provides an overview of the datasets, methodology, and key findings. For further analysis, refer to the detailed code and outputs in the provided notebooks.

