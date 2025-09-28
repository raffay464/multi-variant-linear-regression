# Multi-Variant Linear Regression on Daily Routine Data

## 📌 Project Overview 
The goal is to implement a **Multi-Variant Linear Regression model** on a **self-created dataset** representing a 20-day routine.  
The model explores how different lifestyle factors affect productivity.

## 📝 Problem Statement
We need to implement a **Multi-Variant Linear Regression** model on a dataset of our 20 days’ routine.  

- **Independent Variables (Features):**
  - Sleep Hours  
  - Rank of Food Quality (based on healthy food)  
  - Working Hours  
  - Rank of Health Condition  
  - Rank of Mood (based on outside tension)  

- **Dependent Variable (Target):**
  - Rank of Productivity  

Each variable is rated between **1–10**, simulating daily assessments.

## 📊 Dataset
- The dataset was **programmatically generated** to simulate daily records.  
- Each record corresponds to one day.  
- The dependent variable (Productivity) was derived using a hypothetical relationship with independent variables.

## ⚙️ Methodology
1. **Data Generation** – Created a 20-day dataset with controlled random values.
    
2. **Exploratory Data Analysis (EDA)** –  
   - Scatter plots for feature-target relationships  
   - Correlation matrix
     
3. **Model Implementation** –  
   - Multi-variable linear regression from scratch  
   - Implemented **Gradient Descent** optimization  
   - Visualized parameter updates and cost reduction
     
4. **Evaluation**
   – Checked convergence of the cost function and parameter stability.

## 📈 Results
- The model successfully converged, showing a decreasing cost function.  
- Parameters stabilized after sufficient iterations.  
- Initial results showed limited insight due to low variability in the target variable, highlighting the need for better dataset simulation.  

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/raffay464/multi-variant-linear-regression.git

2. open notebook:
   jupyter notebook "Multi-variant LR.ipynb"
   
3. Run the cells step by step to see:
  - Dataset creation
  - Exploratory Data Analysis
  - Gradient Descent implementation
  - Training results   

4. Repository Contents
  - Multi-variant LR.ipynb → Jupyter notebook with implementation.
  - Report.docx → Project report with methodology, results, and conclusion.
  - README.md → Documentation for project.
  - dataset/ (optional) → Store CSV if dataset is exported.

## Learnings 
  - Implementing Linear Regression from scratch builds deeper understanding of gradient descent.
  - Data quality is crucial — constant or unrealistic target values can make analysis meaningless.
  - Future improvements: better dataset design, larger sample size, and model validation.
