## Market Basket Analysis using Python

📌 **Project Overview**
This project focuses on Market Basket Analysis using retail transaction data from the Online Retail Dataset. The analysis aims to uncover customer purchasing patterns by identifying products that are frequently bought together. Raw transaction data is cleaned, transformed into a basket matrix using one-hot encoding, and analyzed using the Apriori algorithm to generate association rules based on support, confidence, and lift.
The results are interpreted to provide business-oriented insights that support cross-selling, product bundling, recommendation systems, and product placement strategies.

🎯 **Objectives**
* Analyze retail transaction data to understand customer purchasing behavior
* Identify frequent product combinations using Market Basket Analysis
* Transform transaction data into a basket matrix format
* Apply the Apriori algorithm to generate frequent itemsets and association rules
* Produce actionable business insights to improve sales strategies and Average Order Value (AOV)

📊 **Key Metrics Analyzed**
* Total number of transactions (order_id)
* Total number of unique products (product_name)
* Number of products per transaction
* Basket matrix representation (True/False per product per transaction)
* Support, confidence, and lift values from association rules

🔍 **Key Insights**
* Most transactions consist of a single product, indicating strong single-item purchasing behavior.
* Multi-product transactions occur less frequently but provide valuable insights into product relationships.
* Basket matrix transformation enables accurate identification of product associations.
* Several product pairs show strong associations and can be leveraged for cross-selling, bundling, and recommendation strategies.

🛠 **Tools Used**
* Python (Pandas, NumPy, mlxtend)
* Jupyter Notebook
* Dataset: Online Retail Dataset (Kaggle, simulated / non-real data)
* Presentation: PowerPoint (Market Basket Analysis Report)

📂 **Project Deliverables**
* Jupyter Notebook containing the full analysis workflow
* Cleaned and preprocessed transaction dataset
* Basket matrix (transaction × product)
* Frequent itemsets and association rules
* Business insights and recommendations
* Presentation slide deck summarizing methodology and results

📝 **Notes**
* This project emphasizes data preparation, Market Basket Analysis, and association rule mining.
* No supervised or predictive machine learning models are used in this project.
* The dataset is not real transaction data and is intended for educational and analytical purposes only.
* Future enhancements may include advanced recommendation systems or deeper analysis of customer segments.
