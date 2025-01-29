# 🏆 FIFA21 Data Cleaning Project  

## 📌 Project Overview  
Raw data is often messy, inconsistent, and filled with missing values. This project focuses on **cleaning and preprocessing the FIFA21 dataset**, ensuring it is structured, consistent, and ready for analysis.  

## 🎯 Objectives  
- Handle **missing values** and **duplicates**  
- Convert **incorrect data types** (height, weight, wages, etc.)  
- Extract and clean **contract details**  
- Standardize **monetary values** (€ conversions)  
- Ensure **data integrity** for further analysis  

## 📊 Dataset  
- **Source:** [FIFA21 Messy Dataset on Kaggle](https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring)  
- **Size:** ~18,979 players, 77 features  
- **Format:** CSV  

## 🛠️ Technologies Used  
- **Python** (pandas, numpy)  
- **Data Visualization:** seaborn  
- **Jupyter Notebook**  

## 📂 Repository Structure  
```
Comprehensive Data Cleaning of FIFA21 Player/
│── data/
│   ├── raw/                  # Original messy dataset
│   │   ├── fifa21_raw_data.csv
│   ├── processed/             # Cleaned dataset
│   │   ├── fifa21_cleaned.csv
│
│── notebooks/
│   ├── fifa21_data_cleaning.ipynb  # Jupyter Notebook
│
│── reports/
│   ├── FIFA21_Data_Cleaning_Report.pdf  # Project documentation
│
│── images/
│   ├── logo.jpeg
│
│── README.md                  # Project overview
│── requirements.txt            # Python dependencies
│── .gitignore                  # Ignore unnecessary files
```

## 🔍 Data Cleaning Steps  
✔ **Handling Missing Values:**  
- Imputed `Loan Date End` missing values with `"Not Present"`  
- Checked and handled missing values using heatmaps  

✔ **Removing Duplicates:**  
- Identified duplicate rows and removed them  

✔ **Fixing Data Types:**  
- Converted height from **feet & inches → inches**  
- Converted weight from **"lbs" → integer**  
- Standardized `Joined` column to **datetime**  

✔ **Monetary Values Conversion:**  
- Cleaned `Wage`, `Release Clause`, and `Value` by:  
  - Removing `€` symbols  
  - Multiplying `K` by 1,000 and `M` by 1,000,000  
  - Converting to **integer format**  

✔ **Feature Engineering:**  
- Extracted **Team & Contract** details  
- Removed special characters (`★`) from rating columns  
- Standardized **SM, W/F, IR** ratings to **integers**  

## 📈 Results & Insights  
- The cleaned dataset is now **fully structured**, **free of inconsistencies**, and **ready for analysis**  
- Standardized **monetary** and **player attributes** enable accurate player comparison  
- Improved **data integrity** for future **machine learning models**  

## 🚀 How to Run  
### **Option 1: Run Jupyter Notebook**  
1. Clone this repository  
   ```bash
   git clone https://github.com/waqas-liaqat/Comprehensive-Data-Cleaning-of-FIFA21-Player.git
   cd FIFA21-Data-Cleaning
   ```
2. Install required dependencies  
   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook  
   ```bash
   jupyter notebook
   ```
4. Run `notebooks/fifa21_data_cleaning.ipynb`  


## 📌 Next Steps  
🔹 Perform **EDA (Exploratory Data Analysis)**  
🔹 Build **Machine Learning Models** for player performance predictions  
🔹 Create a **Power BI/Tableau Dashboard** for FIFA21 player insights  

## 🤝 Connect with Me  
👤 **Muhammad Waqas**  
📧 Email: [waqasliaqat630@gmail.com](mailto:waqasliaqat630@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/muhammad-waqas-liaqat/)  
📂 [GitHub](https://github.com/waqas-liaqat)  
📊 [Kaggle](https://www.kaggle.com/muhammadwaqas630)  

---

If you find this project useful, don’t forget to ⭐ the repo! 🚀  

#DataScience #Python #DataCleaning #MachineLearning #FIFA21 #Analytics  
