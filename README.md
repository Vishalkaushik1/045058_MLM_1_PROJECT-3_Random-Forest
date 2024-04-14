# 045058_MLM_1_PROJECT-3_Random-Forest
# Fashion Product Classification with Random Forest and Decision Tree

Overview:

This repository is dedicated to the exploration and application of Random Forest and Decision Tree models in the classification of fashion products. The goal is to analyze the performance of these models on a dataset of fashion items, identifying key product attributes that drive classification accuracy and provide insights into product segmentation.

Problem Statements:
1. Assess the ability of Random Forest and Decision Tree models to classify products into correct fashion categories.
2. Evaluate and compare the performance of the two models based on accuracy, precision, and recall.
3. Investigate the impact of product attributes on classification outcomes.
4. Derive managerial insights that can aid in inventory categorization, pricing strategy, and marketing.

Data Description:

*Source and Size*
- Data Source: [Fashion Dataset](https://www.kaggle.com/datasets/imrulhasanrobi/e-commerce-big-dataset-from-multi-category)
- Data Size: 7.71 MB
- Data Shape: 61201rows × 10 columns

*Variables:*
1. *Categorical Variables*
   - brand_name: Brand associated with the product.
   - title: Product title or description.
   - Gender: Target gender demographic for the product.
   - productType: Type of product, such as accessories, clothing, etc.
   - cluster: Grouping of the product based on features.
2. *Numerical Variables*
   - current_price: The current selling price of the product.
   - previous_price: Price before any adjustments such as discounts.
   - rrp: Recommended retail price suggested by the brand.
   - productCode: Unique code identifying each product.

Data Analysis:

*Preprocessing*
- Perform imputation for missing data where necessary.
- Encode categorical features suitably for model ingestion.
- Normalize or scale numerical variables to ensure model accuracy.
- Create training and testing datasets for model evaluation.

*Model Building and Evaluation*
- Build a Decision Tree model and a Random Forest model using the preprocessed data.
- Optimize model parameters through cross-validation and grid search.
- Use accuracy, precision, recall, and the confusion matrix to measure model performance.

Results and Insights:
- Present a detailed comparison of the Decision Tree and Random Forest model performance.
- Discuss the importance rankings of the features for both models.
- Provide insights on how these models can be used to inform real-world business strategies in fashion retail.

GitHub Repository Content
- decision_tree.py: Script for the Decision Tree model.
- random_forest.py: Script for the Random Forest model.
- data: Folder containing the dataset used for model training and testing.
- models: Folder where trained model files are saved.
- analysis: Folder containing Jupyter notebooks or scripts used for exploratory data analysis and visualization.
