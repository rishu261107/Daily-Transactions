# 📊 Daily Transactions Analysis

A data analysis project that processes daily transaction records to uncover spending patterns, perform data cleaning, and visualize insights.  
Built with **Python**, **Pandas**, **Matplotlib**, **Seaborn**, and **Plotly**.

---

## 🚀 Features
- **Data Import**: Load transaction datasets in CSV format.
- **Data Cleaning**:  
  - Fill missing `Subcategory` with `Unknown`.  
  - Fill missing `Note` with `No Description`.  
  - Convert `Date` to proper datetime format.  
  - Convert `Amount` to numeric values.
- **Exploratory Data Analysis (EDA)**: Identify patterns, trends, and outliers.
- **Visualization**: Create interactive and static charts for transaction insights.
- **Category & Subcategory Analysis**: Breakdown of spending by categories.

---

## 🛠 Tech Stack
- **Programming Language**: Python 3
- **Libraries Used**:
  - `pandas` – Data manipulation
  - `numpy` – Numerical computations
  - `matplotlib` – Data visualization
  - `seaborn` – Statistical data visualization
  - `plotly` – Interactive visualization
  - `google.colab` – File upload in Colab

---

## 📂 Project Structure
```
Daily_Transactions.ipynb   # Main Jupyter Notebook with analysis code
README.md                  # Project documentation
transactions_sample.csv    # Example dataset (if available)
```

---

## 📦 Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/daily-transactions-analysis.git
   cd daily-transactions-analysis
   ```
2. Install required Python packages:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```

---

## ▶️ Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Daily_Transactions.ipynb
   ```
2. Upload your CSV file when prompted (if using Google Colab).
3. Run all cells to perform:
   - Data Cleaning
   - Exploratory Data Analysis
   - Visualization

---

## 📊 Example Insights
- Total spend per category and subcategory.
- Monthly and daily spend trends.
- High-value transaction detection.
- Interactive charts with Plotly for deeper exploration.
