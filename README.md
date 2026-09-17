# German Car Market Data Analysis

A Python-based exploratory and statistical analysis of German car listings, focused on identifying patterns and relationships across vehicle price, horsepower, mileage, fuel type, gearbox, production year, and offer type.

## Project Overview

This project analyzes a dataset of German car listings sourced from AutoScout24 and made available through Kaggle. The dataset contains information about vehicle characteristics such as:

- Make and model
- Price
- Mileage
- Horsepower
- Fuel type
- Gearbox type
- Production year
- Offer type

The analysis focuses on data cleaning, exploratory data analysis, statistical analysis, and visualization to identify meaningful trends and relationships within the automotive market.

## Dataset

- **Source:** AutoScout24
- **Dataset:** Cars in Germany
- **Period:** 2011–2021
- **Original Records:** 46,405
- **Original Features:** 9
- **Collection Method:** Web scraping
- **Kaggle Dataset:** Cars Germany

## Technologies Used

- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computing
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Interactive analysis environment
- **SciPy / Statistical Methods** – Statistical testing and relationship analysis

## Analysis Workflow

### 1. Data Cleaning

The dataset was examined for quality issues before analysis.

Key preprocessing activities included:

- Identifying missing values in `model`, `gear`, and `hp`
- Handling missing and inconsistent values
- Replacing invalid fuel-type values
- Checking unusual horsepower values
- Reviewing data types and inconsistencies
- Preparing the dataset for exploratory and statistical analysis

### 2. Exploratory Data Analysis

The project investigates the distribution and characteristics of German car listings through visualizations and descriptive statistics.

Areas analyzed include:

- Horsepower distribution
- Vehicle price distribution
- Fuel-type representation
- Offer types
- Gearbox distribution
- Production-year trends
- Price categories
- Mileage patterns

### 3. Statistical Analysis

Statistical methods were used to investigate relationships between variables.

The analysis examines:

- Correlation between price and horsepower
- Relationship between price and mileage
- Relationship between price and production year
- Relationship between gearbox type and price
- Statistical significance of selected relationships
- Correlation patterns between numerical variables

## Key Insights

Some of the major observations from the analysis include:

- Approximately 75% of vehicles have less than 150 horsepower.
- Horsepower and vehicle price show a strong positive correlation, with a correlation coefficient of approximately 0.75.
- Higher-horsepower vehicles are more likely to produce extreme price values.
- Vehicles priced below €10,000 form a substantial portion of the dataset.
- Manual transmissions are more common among lower-priced vehicles, while automatic transmissions become more represented as vehicle price increases.
- The representation of electric and hybrid vehicles increases with production year.
- A notable change in the representation of diesel and gasoline vehicles occurs around 2017.
- Vehicles priced below €20,000 show a higher representation of manual transmission, while automatic transmission becomes more common at higher price levels.

## Project Structure

```text
German-Car-Analysis/
│
├── German-cars-Analysis.ipynb
├── original dataset.csv
└── README.md
