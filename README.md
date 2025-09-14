# 📊 Stack Overflow Developer Survey 2018 – Data Analysis

This project analyzes the **2018 Stack Overflow Developer Survey** dataset to uncover insights about developers’ education, jobs, programming languages, and salaries worldwide.  
It focuses on answering key questions such as:
- How do developers view coding as a hobby?  
- Which countries have the highest Python adoption?  
- What are the average salaries across countries?  
- How does education and years of experience affect pay?  

---

## 📂 Dataset
- **Source**: [Stack Overflow Developer Survey 2018](https://www.kaggle.com/datasets/stackoverflow/stack-overflow-2018-developer-survey)  
- **Files**:
  - `survey_results_public.csv`: survey responses  
  - `survey_results_schema.csv`: schema/column descriptions  
- **Size**: ~98,000 responses  

---

## ⚙️ Project Workflow
1. **Data Loading**  
   - Download dataset from Kaggle using API  
   - Load CSV files with Pandas  

2. **Exploration & Cleaning**  
   - Inspect dataset shape, columns, and data types  
   - Check for missing values (NaN percentage per column)  
   - Explore schema for column definitions  

3. **Analysis**  
   - Developer hobbies and participation in Stack Overflow  
   - Country-wise distributions of developers  
   - Education & job role analysis  
   - Salary analysis across countries  
   - Language usage (focus on **Python adoption**)  

4. **Aggregations & Grouping**  
   - Country-level mean/median salary comparisons  
   - Filtering specific groups (e.g., German engineers with 3–5 years’ experience)  
   - Identifying countries with the most Python developers  

5. **Visualizations** *(optional to extend)*  
   - Participation counts  
   - Salary distributions  
   - Top 10 Python-using countries  

---

## 📈 Example Insights
- % of developers who code as a hobby  
- Number of participants per country  
- Countries with the highest share of Python developers  
- Salary comparisons across different countries and experience levels  

---

## 📊 Sample Results
### 🔹 Top 10 Countries by Python Developers
The project identifies the top 10 countries where Python is most used among developers.  

### 🔹 Salary Insights
- Mean and median salary per country  
- Salary differences based on **years of professional coding**  

---

## 🛠️ Tech Stack
- **Python 3**
- **Libraries**:  
  - `pandas` → data wrangling  
  - `numpy` → numerical operations  
  - `matplotlib`, `seaborn` → visualization  
  - `kaggle` → dataset download  

---

## 📌 How to Run
1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/stackoverflow-survey-2018.git
   cd stackoverflow-survey-2018
