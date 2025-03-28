# Salary Predictor for Data Science Jobs on Glassdoor

📚 **Course**: CIS600 – Principles of Social Media and Data Mining  
🏫 **University**: Syracuse University  
👩‍💻 **Authors**: Titas Ghosh, Fathima Sania, Saad Shah  
🗓️ **Semester**: Spring 2024

---

## 📘 Project Overview

This project presents a predictive analytics tool designed to estimate salaries for data science job roles based on listings from Glassdoor. The goal is to help students and early-career professionals understand current salary trends and the impact of various job features such as skills, title, company rating, and location. The project is built using Python and incorporates two major modules: data preprocessing and model building.

---

## 🧪 Key Features

- Cleans and transforms messy salary, location, and company data
- Extracts key job features from unstructured descriptions
- Engineers important indicators such as `avg_salary`, job alignment, and skill flags
- Implements and compares multiple regression models:
  - Linear Regression
  - Lasso Regression
  - Random Forest Regression
- Uses `GridSearchCV` for hyperparameter tuning
- Visualizes salary distributions and feature importance
- Provides a user-accessible Flask API endpoint (optional extension)

---

## 📁 File Descriptions

| File                             | Description |
|----------------------------------|-------------|
| `Project-Data-cleaning.ipynb`    | Cleans and transforms raw Glassdoor job data |
| `Project-Model-building.ipynb`   | Builds and evaluates ML models for salary prediction |
| `SMDM_project_Paper.pdf`         | Final project paper/report detailing the full methodology and findings |

---

## 📊 Technologies & Libraries Used

- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib & Seaborn** – Data visualization  
- **Scikit-learn** – ML models & evaluation  
- **Statsmodels** – Statistical regression  
- **Flask (optional)** – API for deploying predictions

---

## 📈 Sample Output Highlights

- Graphs comparing salary ranges across job titles  
- MAE evaluation for Linear, Lasso, and Random Forest models  
- Feature importance breakdown (skills, company age, job location)

---

## 💡 Future Improvements

- Incorporate more real-time job data via Glassdoor APIs or scraping tools  
- Improve feature engineering with NLP for more detailed skill extraction  
- Extend API for user-facing deployment (e.g., salary prediction web app)

---

## 📂 How to Run

1. Clone the repo or upload the `.ipynb` files to Google Colab  
2. Install required packages (if not already):
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```
3. Open `Project-Data-cleaning.ipynb` and execute all cells to clean the data  
4. Then open `Project-Model-building.ipynb` and run the model analysis pipeline  

---

## Acknowledgment

This project was completed under the guidance of **Prof. Saman Priyantha Kumarawadu** as part of the CIS600 course at Syracuse University. We thank him for his valuable feedback and support throughout this work.
