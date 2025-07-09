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

##  Architecture Diagram

```mermaid
graph TD
    A[Raw Parking Data (CSV)] --> B[Data Cleaning & Preprocessing]
    B --> C[Feature Engineering]
    C --> D[Model Selection]
    D --> E[XGBoost Regressor]
    E --> F[Model Evaluation (R^2, RMSE)]
    F --> G[Hourly Price Prediction]
    G --> H[Result Visualization & Submission]
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
notebook.ipynb: Jupyter Notebook containing the full workflow

data/: Folder containing the dataset

README.md: Project overview and documentation

architecture.png: (Optional) Exported Mermaid diagram

Report.pdf: (Optional) Final report submitted for evaluation

✅ Ensure all files run without errors before pushing. Test the notebook from top to bottom using Restart & Run All.

🔓 Repository Access
The repository should be set to Public

Alternatively, provide access to reviewers using their GitHub usernames

markdown
Copy
Edit

Let me know if you’d like help:
- Writing a 1-page PDF report for upload
- Exporting the Mermaid diagram to `.png`
- Cleaning and structuring your Colab notebook into `.py` or `.ipynb`
- Creating a `.gitignore` or `requirements.txt` for upload

Just share the GitHub repo name or folder structure if you want help organizing it.
