# Customer Experience Analysis 

Bu proje, Customer Experience Dataset üzerinde temel veri analizi, eksik değer ve aykırı değer tespiti, istatistiksel özet ve görselleştirme adımlarını içermektedir.

## 🗂️ Dataset Description

The dataset includes 1,000 synthetic customer records with the following key features:

- **Demographics**: Age, Gender, Location
- **Interactions**: Number of Interactions, Feedback Score, Products Purchased
- **Behavioral**: Products Viewed, Time Spent on Site
- **Satisfaction & Retention**: Satisfaction Score, Retention Status

### Sample Data

| Customer_ID | Age | Gender | Location | Num_Interactions | Feedback_Score | Products_Purchased | Products_Viewed | Time_Spent_on_Site | Satisfaction_Score | Retention_Status |
|-------------|-----|--------|----------|------------------|----------------|--------------------|-----------------|--------------------|--------------------|------------------|
| 1           | 56  | Male   | Urban    | 11               | 4              | 18                 | 38              | 18.32              | 7                  | Retained         |

---

## 📊 Analysis Overview

### ✅ 1. Statistical Summary
- Measures of central tendency (mean, median)
- Measures of dispersion (std, min, max)
- Distribution shape analysis

### ⚠️ 2. Missing Value Analysis
- Detection of null/missing values
- Imputation strategies discussed: mean/mode fill, KNN, or removal

### 🚨 3. Outlier Analysis
- Boxplot and IQR method used for detection
- Suggestions on handling (capping/trimming)

### 📈 4. Visualizations
- Histograms for distributions (age, satisfaction)
- Boxplots for outlier analysis
- Countplots for categorical data (gender, retention)
- Pair plots & heatmaps for correlation insights

---

## 💾 Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- GitHub
- Scikit-learn (for preprocessing)

---

## 📂 Project Structure

customer-experience-analysis/
│
├── customer_experience_data.csv
│
├── customer_experience.ipynb
│ 
├── README.md
└── requirements.txt


## 🚀 How to Run

1. Clone the repo:  
   `git clone https://github.com/sakirbetull/customer-experience-analysis.git`

2. Install requirements:  
   `pip install -r requirements.txt`

3. Run the Jupyter notebook:
   `jupyter notebook /customer_experience.ipynb`

---

## ✍️ Author

**Betül ŞAKIR**  
GitHub: [@sakirbetull](https://github.com/sakirbetull)  
Email: sakirbetul@outlook.com




