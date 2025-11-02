# Lesson 5 – Titanic Dataset Exploratory Data Analysis

This project demonstrates the use of **Pandas** for data manipulation and **Matplotlib** for data visualization, using the classic **Titanic dataset**.  
It was completed as part of Lesson 5 in the Data Analytics & AI course.

---

## 📘 Objectives
- Load and explore the Titanic dataset  
- Clean and preprocess missing values  
- Create new derived features (`PclassCategory`, `CabinCategory`, `Family`)  
- Analyze survival patterns by demographic and class  
- Use visualization to uncover relationships in the data  

---

## 🧹 Data Cleaning
- Filled missing values in the `Age` column using the mean  
- Extracted deck letters from the `Cabin` column (fallback: “Unknown”)  
- Created a categorical `PclassCategory` from passenger class (1, 2, 3)  
- Computed `Family` size as `SibSp + Parch + 1`  

---

## 📊 Visualizations
- **Histogram** of passenger ages  
- **Bar chart** of survival rates by class  
- **Heatmap** of correlations between numerical features  
- **Pair plot** (scatter matrix) of `Age`, `Fare`, `SibSp`, and `Parch`  
- **Box plot** of age distribution by class and sex  
- **Violin plot** of fare distribution by survival status  

---

## 💡 Key Insights
- Higher survival among **females** and **1st-class** passengers  
- **Fare** and **Pclass** show strong inverse correlation  
- Most passengers were aged **20–35 years**  
- A few high-fare outliers correspond to shared luxury cabins  

---

## 🛠️ Tools Used
- Python 3  
- Pandas  
- NumPy  
- Matplotlib  


---

## 📂 Files Included
- `Lesson_5_Assignment.ipynb` – main Colab notebook  
- `titanic_cleaned.csv` – cleaned dataset 
- `README.md` – project summary  

---

## 📎 Author
**Adetola Ridwat Odulaja**  
Diploma in Data Analytics & AI, Willis College, Ottawa  
