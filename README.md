# Unemployment in India — Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on unemployment data in India to identify regional differences, monthly trends, and changes observed during the early COVID-19 pandemic.

Using Python and data visualization libraries in **Google Colab**, the project explores unemployment rates, estimated employment, and labour force participation across Indian states and regions.

## 🎯 Objectives

- Analyze the structure and quality of the unemployment dataset.
- Identify and handle missing values.
- Calculate average unemployment rates across regions.
- Examine monthly unemployment trends.
- Compare unemployment trends across selected states.
- Identify the top 10 regions with the highest average unemployment rates.
- Analyze correlations between unemployment, estimated employment, and labour participation.
- Compare unemployment indicators before COVID-19 and during the early pandemic period.
- Visualize findings through charts and statistical summaries.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Analysis:** pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Development Environment:** Google Colab
- **Dataset Format:** CSV

## 📂 Project Structure

```text
Unemployment_EDA/
│
├── Unemployment in India.csv
├── Unemployment_EDA.ipynb
└── README.md
```

**Note:** The `.ipynb` file is the notebook downloaded from Google Colab. You do not need to install Jupyter Notebook to run the project in Google Colab.

## 📊 Dataset Description

The project uses the `Unemployment in India.csv` dataset, which contains information about unemployment rates, estimated employment, labour participation, and regional classifications.

| Column | Description |
|---|---|
| Region | Indian state or region |
| Date | Date of observation |
| Frequency | Reporting frequency |
| Estimated Unemployment Rate (%) | Estimated unemployment rate |
| Estimated Employed | Estimated number of employed people |
| Estimated Labour Participation Rate (%) | Estimated labour participation rate |
| Area | Rural or urban classification |

The uploaded dataset covers approximately May 2019 to June 2020, allowing analysis of the period before COVID-19 and the early pandemic period.

**Note:** The dataset does not contain a separate employment-rate percentage column. The analysis uses the estimated employed population count as an employment-related indicator.

## 🚀 How to Run the Project

### Option 1: Run in Google Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Click **File → Upload notebook**.
3. Select `Unemployment_EDA.ipynb`.
4. Upload `Unemployment in India.csv` when required, or place it in your Google Drive.
5. If the notebook uses Google Drive, mount your drive and update the dataset path accordingly.
6. Run the notebook cells sequentially using **Runtime → Run all**.

### Option 2: Run Locally

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `Unemployment_EDA.ipynb`, keep the CSV in the correct directory, and execute the cells sequentially.

## 🔍 Exploratory Data Analysis

### 1. Data Loading and Inspection
- Load the CSV dataset using pandas.
- Inspect rows, columns, and data types.
- Identify missing values.
- Convert dates and numerical fields into appropriate formats.

### 2. Data Cleaning
- Remove unnecessary whitespace from column names.
- Handle missing values in essential columns.
- Convert dates and numerical columns.
- Sort observations chronologically.

### 3. Region-wise Unemployment Analysis
Calculate average unemployment rates for each region to identify differences across the available observations.

### 4. Monthly Trend Analysis
Create a time-series line chart to examine monthly unemployment fluctuations, including changes during the early pandemic period.

### 5. State-wise Comparison
Compare unemployment trends for Maharashtra, Delhi, and Tamil Nadu using a line chart.

### 6. Top 10 Regions
Rank the ten regions with the highest average unemployment rates and visualize the results using a horizontal bar chart.

### 7. Correlation Analysis
Generate a correlation heatmap using unemployment rate, estimated employed population, and labour participation rate.

### 8. Pre-COVID vs. Early-Pandemic Comparison
Compare average unemployment and other available indicators for:

- **Pre-COVID:** Before 1 March 2020.
- **Early pandemic:** From 1 March 2020 onward.

The comparison is descriptive and does not independently establish the causal effect of COVID-19.

## 📈 Visualizations

The project includes:

1. Average unemployment rate by region.
2. Monthly unemployment trend.
3. State-wise unemployment comparison.
4. Top 10 regions by average unemployment rate.
5. Correlation heatmap.
6. Pre-COVID versus early-pandemic statistical comparison.

## 💡 Expected Outcomes

- Understand regional differences in unemployment.
- Identify monthly fluctuations and changes during the early pandemic.
- Compare unemployment patterns across selected states.
- Identify regions with high average unemployment rates.
- Examine relationships between unemployment and labour indicators.
- Quantify differences between pre-COVID and early-pandemic average rates.

## ⚠️ Limitations

- The dataset covers approximately May 2019 to June 2020.
- It does not provide long-term post-COVID observations.
- Missing data may affect calculated averages.
- Estimated employed population is a count, not an employment-rate percentage.
- Correlation does not imply causation.
- The observed changes cannot be attributed exclusively to COVID-19 using this analysis alone.

## 🔮 Future Improvements

- Include more recent unemployment data.
- Compare rural and urban unemployment separately.
- Build an interactive dashboard using Streamlit or Plotly.
- Explore unemployment forecasting using time-series models.
- Incorporate additional economic indicators.

## 👨‍💻 Author

**Name:** Rohan Bhosale

**Project:** Unemployment in India — Exploratory Data Analysis

**Domain:** Data Analysis and Visualization

**Platform:** Google Colab

## 📄 License

This project is intended for educational and analytical purposes. Check the original dataset's licensing terms before redistributing it or using it commercially.
