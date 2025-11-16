# Breast Cancer Analysis Notebook

## Overview
This notebook analyzes the **Breast Cancer Wisconsin dataset** (diagnosis: malignant or benign) and visualizes key features. It includes:

- Data preprocessing and cleaning
- Exploratory data analysis (EDA)
- Feature importance using Random Forest
- Correlation heatmap
- Top features analysis

## Dataset
- Source: [Wisconsin Breast Cancer Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Features include: radius, perimeter, area, smoothness, concavity, concave points, etc.
- Target: `diagnosis` (Malignant = M, Benign = B)

## Key Findings
- Tumor size features (`radius_mean`, `perimeter_mean`, `area_mean`) are the most predictive of malignancy.
- Shape irregularities (`concavity_mean`, `concave points_mean`) provide additional predictive value.
- Other features like smoothness or texture contribute minimally.

## How to Use
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/yourrepo.git
