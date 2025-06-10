# Walmart Sales EDA Case Study

This project provides an exploratory data analysis (EDA) on Walmart's sales performance, aiming to uncover patterns in product categories, profitability, regions, and seasonal demand.

# Objectives

- Explore sales trends across product categories
- Identify high and low performing regions
- Detect seasonal influences on revenue
- Support inventory and marketing decisions

# Dataset Features

Typical columns include:
- **Date** – Time of sale  
- **Region** – Sales location  
- **Product_Category** – Type of item  
- **Sales** – Revenue generated  
- **Profit** – Profit margins  
- **Quantity** – Units sold

# Key Insights

- Certain product categories outperform others in winter months
- Southern region shows strong average profits per transaction
- Electronics and Office Supplies see sharp Q4 sales peaks

# Visualizations

- Monthly sales trend line
- Region-wise bar chart for profit
- Category breakdown with pie and count plots
- Heatmap of correlation among numeric variables

# Business Recommendations

- Increase stock of top-performing categories before seasonal peaks
- Focus promotions in underperforming regions with high traffic
- Reduce inventory for categories with negative profit margins

## Installation

Install Python dependencies using:

```bash
pip install -r requirements.txt
```

Refer to the provided `requirements.txt` for the full list of dependencies.

## Download Dataset & Run Notebook

Download the dataset from Kaggle. You will need a Kaggle account to accept the
license terms and access the files. After logging in you can either download
`walmart_data.csv` manually from the
[Black Friday Sales Dataset](https://www.kaggle.com/datasets/sainijuneja/black-friday-sales-dataset)
page or use the Kaggle API:

```bash
kaggle datasets download -d sainijuneja/black-friday-sales-dataset -f walmart_data.csv
unzip black-friday-sales-dataset.zip
```

Then launch the notebook:

```bash
jupyter notebook Walmart-EDA-CaseStudy.ipynb
```


# Tools Used

- Python (Pandas, NumPy)
- Matplotlib & Seaborn
- Jupyter Notebook

---

> 👤 By [Sarath Chandra](https://github.com/Sarathchandrrra)

## Dataset License

The `walmart_data.csv` file analyzed in the notebook comes from the
[Black Friday Sales Dataset](https://www.kaggle.com/datasets/sainijuneja/black-friday-sales-dataset)
hosted on Kaggle. It is distributed under the
[Creative Commons Attribution 3.0 License](https://creativecommons.org/licenses/by/3.0/),
which permits redistribution and modification with attribution. Because of
its size the dataset is not included in this repository; you will need a Kaggle
account to accept the terms and download `walmart_data.csv` from the Kaggle page.
Place the file in the project directory before running the notebook.

## License

This project is licensed under the [MIT License](LICENSE).
