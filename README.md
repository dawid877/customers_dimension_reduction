## Customers Data Dimension Reduction Project

The goal of this project is to reduce the dimensionality of a dataset sourced from Kaggle, which contains characteristics of online customers from an e-commerce platform.  
The objective was to identify latent factors for effective e-customer segmentation.

 **Dataset:** [Kaggle - Customer Segmentation](https://www.kaggle.com/datasets/somesh140/segmentation)

Data preprocessing was particularly challenging due to the high dimensionality (29 variables) and the mixed data types — both numerical and categorical.

To perform dimensionality reduction, the following techniques were applied:
- **Principal Component Analysis (PCA)** for numerical variables
- **Factorial Analysis of Mixed Data (FAMD)** to handle mixed variable types (numerical + categorical)

---

## Tech Stack
- **Language:** R  
- **Key Packages:** `factoextra`, `ggplot2`, `corrplot`, `FactoMineR`

---

## Project Structure
- `Dimension_Reduction_Final.ipynb` — The core R notebook  
- `Dimension_Reduction_Final.html` — Exported HTML version of the notebook  
- `customer_data.csv` — Original dataset  
  > This file must be in the same directory when running the notebook
