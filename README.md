# Customer Shopping Behaviour Analysis

## Overview

This project analyzes customer shopping behaviour using **Python, Pandas, MySQL, and Power BI**. It involves data cleaning, exploratory data analysis (EDA), SQL-based data analysis, and interactive dashboard development to understand customer purchasing patterns and support data-driven decision-making.

## Dataset

The project uses `customer_shopping_behavior.csv`, which contains customer shopping and purchasing information.

Key areas explored include:
- Customer demographics and age groups
- Product categories and purchase amounts
- Purchase frequency and shopping patterns
- Discounts, promotional codes, and review ratings

## Tools & Technologies

- **Python** – Data analysis and preprocessing
- **Pandas** – Data manipulation and cleaning
- **Jupyter Notebook** – Exploratory data analysis
- **MySQL** – Data storage and SQL querying
- **SQLAlchemy & MySQL Connector** – Database connectivity
- **Power BI** – Interactive dashboard and visualization

## Project Workflow

1. **Data Loading:** Imported the CSV dataset into Python using Pandas.
2. **Exploratory Data Analysis (EDA):** Examined dataset structure, statistical summaries, and missing values.
3. **Data Cleaning:** Handled missing review ratings using category-wise median imputation and standardized column names.
4. **Feature Engineering:** Created age groups and converted purchase frequencies into numerical day intervals.
5. **MySQL Integration:** Connected Python to MySQL and loaded the processed dataset into the `customer` table.
6. **SQL Analysis:** Used SQL queries to retrieve and analyze customer shopping data.
7. **Power BI Dashboard:** Developed an interactive dashboard to present key metrics, customer trends, and purchasing insights.

## Dashboard

The Power BI dashboard provides a visual overview of customer shopping behaviour, helping users explore purchasing patterns and customer preferences.

**Dashboard highlights may include:**
- Customer and purchase metrics
- Purchase amount analysis by product category
- Customer segmentation by age group
- Purchase frequency patterns
- Review ratings and discount usage


## Results

- Cleaned and prepared customer shopping data for analysis.
- Applied feature engineering to create meaningful analytical variables.
- Integrated the processed dataset with MySQL for SQL-based analysis.
- Combined Python, SQL, and Power BI into an end-to-end data analytics workflow.
- Prepared customer behaviour data for interactive visualization and business insights.

## How to Run

### Prerequisites

Install Python and MySQL, and ensure Power BI Desktop is available for dashboard exploration.

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd <your-repository-folder>
```

### 2. Install Dependencies

```bash
pip install pandas mysql-connector-python sqlalchemy jupyter
```

### 3. Prepare the Dataset

Place `customer_shopping_behavior.csv` in the project directory.

### 4. Run the Jupyter Notebook

```bash
jupyter notebook Customer_Shopping_Behaviour.ipynb
```

Execute the notebook cells to load, clean, transform, and analyze the dataset.

### 5. Configure MySQL

- Create a MySQL database named `CUSTOMER_BEHAVIOUR`.
- Update the connection settings in the notebook with your local MySQL credentials.
- Run the database connection and data-loading cells to create and populate the `customer` table.

**Security note:** Do not commit database passwords or other credentials to GitHub. Use environment variables or a local configuration file excluded from version control.

### 6. Open the Power BI Dashboard

Open the `.pbix` dashboard file in Power BI Desktop. Configure the data source if required, refresh the data, and explore the visualizations.

## Skills Demonstrated

`Python` · `Pandas` · `EDA` · `Data Cleaning` · `Feature Engineering` · `MySQL` · `SQL` · `Power BI` · `Data Visualization`


If you find this project useful, feel free to ⭐ the repository.
