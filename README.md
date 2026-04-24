# 🦠 COVID-19 Data Analysis using Python

## 📌 Project Overview
This project analyzes COVID-19 data using Python. It includes data cleaning, processing, and visualization to understand trends such as confirmed cases, deaths, recoveries, and active cases across different countries.

The main objective is to gain insights into the spread and impact of COVID-19 using real-world datasets.

---

## 📊 Features
- Data cleaning and preprocessing
- Handling missing values and outliers
- Country-wise data grouping and aggregation
- Data visualization:
  - Line charts
  - Bar graphs
  - Pie / Donut charts
- Statistical analysis (mean, median, mode)
- Comparison between countries

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Dataset
The dataset includes:
- Confirmed cases
- Deaths
- Recovered cases
- Active cases
- Country/Region data

(Source: Public datasets like Johns Hopkins / Kaggle)

---

## ⚙️ Installation & Setup

1. Clone the repository:
git clone https://github.com/your-username/covid19-data-analysis.git

2. Navigate to the folder:
cd covid19-data-analysis

3. Install dependencies:
pip install pandas numpy matplotlib seaborn

4. Run the project:
python main.py

---

## 📈 Sample Code

### Grouping Data
df.groupby("Country/Region").sum()

### Handling Missing Values
df.fillna(df.mode().iloc[0], inplace=True)

### Pie Chart Example
plt.pie(df['Values'], labels=df['Category'], autopct='%1.1f%%')

---

## 📌 Key Insights
- Countries with highest confirmed cases
- Death rate trends
- Recovery patterns
- Comparison between regions

---

## 🚀 Future Improvements
- Add real-time data updates
- Create interactive dashboard
- Apply machine learning for predictions

---

## 👩‍💻 Author
Dolly Dalal  
PRN: 25070123044  
Division: A  
Batch: ENTC A2  

---

## 📄 License
This project is for educational purposes only.
