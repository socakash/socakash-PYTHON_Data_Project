
# Data Jobs Analysis

This project explores job postings data to answer one key question:

**👉 What are the most in-demand skills for the top 3 most popular data-related job roles?**

By cleaning, transforming, and analyzing a large dataset of job postings, the project identifies high-demand technical skills for **Data Analysts, Data Engineers, and Data Scientists**.  

---

## 📂 Project Structure


---

## 🛠️ Data Cleaning & Preparation

Steps performed on the raw dataset:

1. Converted `job_posted_date` to datetime format  
2. Removed rows with missing skills  
3. Converted skills column from string to Python list using `ast.literal_eval`  
4. Filtered dataset for relevant countries and job roles (focus: Canada & United States)  
5. Exploded `job_skills` list into individual rows for aggregation  

---

## 📊 Analysis Workflow

1. **Clean skills column** – standardize and prepare skills list  
2. **Calculate skill count by job role** – find most frequently mentioned skills  
3. **Plot initial findings** – quick bar charts and counts  
4. **Calculate skill % share** – normalize across roles  
5. **Plot final findings** – highlight top skills by role  

---

## 🔑 Key Findings

- The **top 3 job roles** (by posting volume) are:  
  1. Data Engineer  
  2. Data Analyst  
  3. Data Scientist  

- Across these roles, the **most in-demand skills** are:  
  - **SQL**  
  - **Python**  
  - **Azure**  

---

## 📈 Visualizations

The notebooks generate visual insights including:  
- Skill frequency bar plots  
- Location-based job demand  
- Top companies hiring for each role  
- Salary trends (where available)  

*(Add screenshots of plots here once you’re ready, e.g. skill distribution charts.)*

---

## ⚙️ Tech Stack

- **Python**  
- **Pandas** – data cleaning & manipulation  
- **Matplotlib / Seaborn** – visualizations  
- **Jupyter Notebooks** – interactive analysis  

---

## 🚀 How to Use

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
pip install pandas matplotlib seaborn

---
