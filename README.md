# Task 5: Sales Data Analysis with Pandas

## 📋 Project Overview
This project analyzes sales data using Python's Pandas library to extract insights and create visualizations.

## 🎯 Objective
Analyze sales data to understand:
- Total sales by product
- Regional performance
- Sales trends over time
- Category-wise distribution

## 🛠 Tools Used
- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **Jupyter Notebook / Google Colab** - Development environment

## 📁 Project Structure
```
.
├── sales_analysis.py          # Main Python script
├── sales_data.csv             # Sample sales dataset
├── sales_analysis_charts.png  # Generated visualizations
└── README.md                  # Project documentation
```

## 🚀 How to Run

### Method 1: Using Jupyter Notebook
1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Create a new notebook
3. Copy and paste the code from `sales_analysis.py`
4. Run each cell

### Method 2: Using Google Colab
1. Go to [Google Colab](https://colab.research.google.com/)
2. Create a new notebook
3. Copy and paste the code
4. Run the cells

### Method 3: Using Python Script
1. Install required libraries:
   ```bash
   pip install pandas matplotlib numpy
   ```
2. Run the script:
   ```bash
   python sales_analysis.py
   ```

## 📊 Key Features

### Data Operations
- ✅ Load CSV using Pandas
- ✅ Display basic statistics
- ✅ Check for missing values (NaN)
- ✅ Filter rows based on conditions
- ✅ Use `groupby()` for aggregation

### Visualizations
- 📊 Bar chart: Sales by Product
- 📊 Horizontal bar chart: Sales by Region
- 🥧 Pie chart: Category distribution
- 📈 Line chart: Sales trend over time

## 🔍 Analysis Insights
The analysis provides:
- Total revenue generated
- Average sale value
- Best-selling products
- Top-performing regions
- Sales trends over time

## 📚 Concepts Covered
- **Pandas DataFrame**: Tabular data structure
- **groupby()**: Group data and perform aggregations
- **loc[] vs iloc[]**: Label-based vs position-based indexing
- **.head()**: Display first n rows
- **Filtering**: Select rows based on conditions
- **Visualization**: Create charts using matplotlib

## 💡 Interview Questions Answers

1. **What is Pandas used for?**
   - Data manipulation, analysis, and cleaning of structured data

2. **What's a DataFrame?**
   - A 2D labeled data structure with columns of potentially different types

3. **How do you read a CSV file?**
   - `pd.read_csv('filename.csv')`

4. **What is groupby()?**
   - Groups data based on column values and performs aggregate functions

5. **How do you filter rows?**
   - `df[df['column'] > value]`

6. **Difference between loc[] and iloc[]?**
   - loc[]: Label-based indexing
   - iloc[]: Position-based indexing

7. **What does .head() do?**
   - Returns first 5 rows (default) of the DataFrame

8. **How can you create a bar chart?**
   - `df.plot(kind='bar')` or `plt.bar()`

9. **What's the shape of a DataFrame?**
   - Returns tuple (rows, columns): `df.shape`

10. **What is NaN?**
    - "Not a Number" - represents missing or undefined values

## 📸 Sample Output
The script generates:
- Console output with detailed analysis
- A comprehensive dashboard with 4 charts saved as PNG

## 👨‍💻 Author
Python Developer Internship - Task 5

## 📅 Date
September 2025

---
**Note**: You can replace the sample data with your own CSV file by modifying the `pd.read_csv()` line.
