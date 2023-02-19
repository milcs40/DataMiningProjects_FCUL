# Data Mining Projects @FCUL
Group projects for the Data Mining Course @FCUL. Consist of three parts: 
- Pattern Mining
- Clustering
- Classification and Regression.

## Project 1 - Pattern Mining
In this project we had to use Python 3, Jupyter Notebook and MLxtend. When using MLxtend, frequent patterns can either be discovered using Apriori and FP-Growth. 
The dataset that we analysed was the [Foodmart_2020_PD.csv](Foodmart_2020_PD.csv), a modified version of the <a href="https://github.com/neo4j-examples/neo4j-foodmart-dataset/tree/master/data"> Foodmart 2000(2005) dataset </a>.

`Foodmart_2020_PD.csv` stores 69549 transactions from 24 stores, where 103 different products can be bought. Each transaction (row) has a STORE_ID (integer from 1 to 24), and a list of produts (items), together with the quantities bought.

The aim was to be creating and answer the following questions:
- What are the most popular products?
- Which products are bought together?
- Can you find associations highliting that when people buy a product/set of products also buy other product(s)?

Includes the Jupyter Notebook ([`PD_201920-Group_16_Pattern_Mining.ipynb`](PD_201920-Group_16_Pattern_Mining.ipynb)) for the Pattern Mining Project.

## Project 2 - Clustering
In this project we had to use use Python 3, Jupyter Notebook and Scikit-learn.

The dataset we had to analyse was the [AML_ALL_PATIENTS_GENES_EXTENDED.csv](AML_ALL_PATIENTS_GENES_EXTENDED.csv). This is an extended version of the widely studied Leukemia dataset, originally published by Golub et al. (1999) <a href="https://pubmed.ncbi.nlm.nih.gov/10521349"> "Molecular Classification of Cancer: Class Discovery and Class Prediction by Gene Expression Monitoring" </a>.

This dataset studies patients with leukaemia. At disease onset clinicials diagnosed them in two different types of leukaemia: acute myeloid leukemia (AML) and acute lymphoblastic leukemia (ALL). Some of these diagnoses were later confirmed, other revealed to be wrong. The data analyzed here contains the expression levels of 5147 Human genes (features/columns) analyzed in 110 patients (rows): 70 ALL and 40 AML. Each row identifies a patient: The first column, ID, contains the patients' IDs , the second column, DIAGNOSIS, contains the initial diagnosis as performed by clinicians (ground truth), and the remaining 5147 columns contain the expression levels of the 5147 genes analysed.

The goal was to cluster patients and (ideally) find AML groups and ALL groups.

Includes the Jupyter Notebook ([`PD_201920_Group_16_Clustering.ipynb`](PD_201920_Group_16_Clustering.ipynb)) for the Pattern Mining Project.

## Project 3 - Classification and Regression
In this project we had to use Python 3, Jupyter Notebook and Scikit-learn. We were also allowed to use Orange3.

The dataset we analysed was the [`ModifiedHousePrices.csv`](ModifiedHousePrices.csv), a modified version of the train dataset used in Kaggle's competition 
<a href="https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview"> "House Prices: Advanced Regression Techniques"</a>.

If you ask a home buyer to describe their dream house, they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence. With more than 70 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

This project challenges you twice with the following tasks:
- Regression Task: predict the price of a house.
- Classification Task: predict a price category of a house.

The targets we had to predict were:

- `SalePrice` - the property's sale price in dollars. This is the target variable that we were trying to predict in the regression task (same as in the Kaggle challenge).
- `Price3Classes` - the price category, where price can be below 200000 ("<200000"), between 200000 and 400000 ("[200000,400000]"), or above 200000 (">200000"). This was the target variable that we were trying to predict in the classification task.

Includes the Jupyter Notebook ([`PD_201920_Group_16_ClassifcationRegression.ipynb`](PD_201920_Group_16_ClassifcationRegression.ipynb)) for the Pattern Mining Project.
