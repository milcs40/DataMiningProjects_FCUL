# Data Mining Projects @FCUL
Group projects for the Data Mining Course @FCUL. Consist of three parts: Pattern Mining; Clustering; Classification and Regression.

## Project 1 - Pattern Mining
In this project we had to use Python 3, Jupyter Notebook and MLxtend. When using MLxtend, frequent patterns can either be discovered using Apriori and FP-Growth. 
The dataset that we analysed was the [Foodmart_2020_PD.csv](Foodmart_2020_PD.csv), a modified version of the <a href="https://github.com/neo4j-examples/neo4j-foodmart-dataset/tree/master/data"> Foodmart 2000(2005) dataset </a>.

`Foodmart_2020_PD.csv` stores 69549 transactions from 24 stores, where 103 different products can be bought. Each transaction (row) has a STORE_ID (integer from 1 to 24), and a list of produts (items), together with the quantities bought.

The aim was to be creating and answer the following questions:
- What are the most popular products?
- Which products are bought together?
- Can you find associations highliting that when people buy a product/set of products also buy other product(s)?

Includes the Jupyter Notebook ([`PD_201920-Group_16_Pattern_Mining.ipynb`](PD_201920-Group_16_Pattern_Mining.ipynb) for the Pattern Mining Project.

## Project 2 - Clustering
Make a Python notebook containing the following sections:
- Dimensions and facts tables of the DW
- Define an ETL workflow
- Do a critical assessment of the work

Includes the Jupyter Notebook ([`TPD_1920_Project_Phase2_Group20_V3.ipynb`](TPD_1920_Project_Phase2_Group20_V3.ipynb)) and the star schema ([`HuGs_Star_Schema.png`](HuGs_Star_Schema.png)) for the HuGS-DW.

## Project 3 - Classification and Regression
Make a Python notebook containing the following sections:
- OLAP queries
- Bottlenecks
- Do a critical assessment of the full project

Includes the Jupyter Notebook ([`TPD_1920_Project_Phase3_Group20.ipynb`](TPD_1920_Project_Phase3_Group20.ipynb)) for the HuGS-DW.
