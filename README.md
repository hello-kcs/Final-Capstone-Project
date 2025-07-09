# Dynamic Pricing for Urban Parking Lots 🚗📊

##  Project Overview

This project was developed as part of the Summer Analytics 2025 Capstone Challenge organized by the Consulting and Analytics Club, IIT Guwahati. The goal is to implement a dynamic pricing model for urban parking lots to optimize revenue while considering demand, occupancy, and other environmental factors. The solution predicts the ideal hourly price for each parking lot using key features such as time of day, location, and utilization.

##  Tech Stack

- **Python**
- **Pandas, NumPy** – Data manipulation
- **Scikit-learn, XGBoost** – Model training and evaluation
- **Matplotlib, Seaborn** – Data visualization
- **Google Colab** – Development environment
- **Git/GitHub** – Version control and collaboration

##  Architecture Diagram (Text Version)

- **Raw Parking Data (CSV)**  
  ⬇  
- **Data Cleaning and Preprocessing**  
  ⬇  
- **Feature Engineering**  
  ⬇  
- **Model Selection (XGBoost Regressor)**  
  ⬇  
- **Model Evaluation (R² Score, RMSE)**  
  ⬇  
- **Hourly Price Prediction**  
  ⬇  
- **Result Visualization and Export**

🔍 Architecture and Workflow
Data Loading and Cleaning:
The dataset was loaded from CSV files, cleaned for null values, incorrect entries, and formatted for consistency.

Feature Engineering:
We extracted and engineered relevant features such as:
Day of week and hour of day
Parking duration and occupancy
Historical pricing trends
Model Building:

After trying linear models and tree-based methods, XGBoost Regressor gave the best performance with optimized hyperparameters.

Evaluation Metrics:
The model was evaluated using:
R-squared (R²)
Root Mean Square Error (RMSE)

Output:
Final predictions were generated for hourly pricing and visualized using line plots for select parking lots.

📄 Documentation
code.ipynb: Jupyter Notebook containing the full workflow
dataset.csv: Dataset provided
README.md: Project overview and documentation
problem_statement.pdf: Problem statement provided





