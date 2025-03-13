# Student Performance Analysis

## 📌 Project Overview
This project aims to analyze student performance data to uncover insights that can help improve academic outcomes. The study involves data cleaning, exploratory data analysis (EDA), identifying correlations, and making data-driven recommendations.

## 📂 Dataset Information
- **Source:** [Kaggle - Student Grading Dataset](https://www.kaggle.com/datasets/mahmoudelhemaly/students-grading-dataset)
- **Key Features:**
  - Demographics: Gender, Age, Department
  - Academic Records: Attendance, Midterm, Assignments, Quizzes, Participation, Projects, Total Score
  - Additional Information: Extracurricular Activities, Internet Access, Parental Education, Family Income Level
- **Target Variable:** Final Grade (A, B, C, etc.)

## 📊 Methodology
The project follows these structured steps:

### 1️⃣ Data Cleaning & Preprocessing
- Removed unnecessary columns.
- Handled missing values (e.g., median imputation for Attendance & Assignments_Avg).
- Checked for duplicate records.

### 2️⃣ Exploratory Data Analysis (EDA)
- Used histograms, scatter plots, and box plots to visualize trends.
- Identified patterns in student performance based on grades and demographics.
- Analyzed outliers and performance variations.

### 3️⃣ Identifying Correlations & Patterns
- Applied statistical techniques (correlation matrix, hypothesis testing).
- Evaluated the impact of internet access, extracurricular activities, and parental education on student performance.

### 4️⃣ Performance Analysis & Insights
- Found that **males** have a higher probability of achieving **A grades**.
- Internet access and extracurricular activities showed minimal impact on total scores.
- Attendance seems to be overweighted in final grading.

## 🚀 How to Run the Notebook
1. **Install Required Libraries**  
   Ensure you have Python installed along with necessary dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. **Run the Notebook**  
   Open Jupyter Notebook and execute `code.ipynb` step by step.
3. **Analyze Visualizations & Insights**  
   Review the plots and summary findings generated from the notebook.

## 📑 Deliverables
- **Jupyter Notebook (`code.ipynb`)** - Contains all analysis and findings.
- **Presentation (`Student_Performance_Challenge_Presentation.pptx`)** - Summarizes insights and recommendations.
- **README (`README.md`)** - Provides an overview of the project.

## 📌 Future Improvements
- Validate the grading formula with domain experts to ensure fair assessment.
- Implement machine learning models to predict student performance.
- Explore additional datasets for comparison and deeper insights.

📩 **For inquiries or feedback, feel free to reach out!** 🚀

