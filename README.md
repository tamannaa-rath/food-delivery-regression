# Food Delivery Time Prediction

## Project Overview
This project focuses on predicting **food delivery time** and analyzing delivery delays using machine learning techniques. The objective is to perform **end-to-end data analysis and predictive modeling**, covering data preprocessing, exploratory data analysis (EDA), feature engineering, regression, classification, evaluation, and actionable insights.

The project is structured following **industry-standard machine learning workflows**, emphasizing modularity, reproducibility, and clarity.

---

## Problem Statement
Food delivery platforms rely heavily on accurate delivery time estimation to improve customer satisfaction and operational efficiency. Delivery time can be influenced by several factors, including customer and restaurant location, traffic conditions, weather, order priority, and delivery personnel experience.

This project aims to:
- Predict the **delivery time** using regression techniques.
- Classify deliveries as **“Fast” or “Delayed”** using logistic regression.
- Analyze the most influential factors affecting delivery performance.

---

## Objectives
- Perform comprehensive **data preprocessing and EDA**.
- Engineer meaningful features that improve model performance.
- Build and evaluate:
  - **Linear Regression** for delivery time prediction.
  - **Logistic Regression** for delivery delay categorization.
- Compare model performance using appropriate metrics.
- Provide **actionable insights** based on analytical results.

---

## Dataset
- **File:** `Food_Delivery_Time_Prediction.csv`
- **Target Variables:**
  - `Delivery_Time` (continuous target for regression)
  - Binary delivery status (Fast vs Delayed) for classification
- **Features include:**
  - Distance
  - Traffic conditions
  - Weather conditions
  - Vehicle type
  - Order priority
  - Time-based variables

Raw data is preserved separately from processed data to ensure traceability and reproducibility.

---

## Project Phases & Methodology

### Phase 1: Data Collection & Exploratory Data Analysis (EDA)
- Data loading and inspection
- Handling missing and inconsistent values
- Descriptive statistics (mean, median, variance)
- Correlation analysis with target variable
- Outlier detection using boxplots

### Phase 2: Feature Engineering
- Distance calculation (Haversine formula if required)
- Encoding categorical variables
- Normalization / standardization of numerical features
- Creation of time-based features (Rush Hour vs Non-Rush Hour)

### Phase 3: Predictive Modeling
#### Linear Regression
- Train-test split (e.g., 80/20)
- Prediction of delivery time
- Evaluation using:
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
  - R² Score

#### Logistic Regression
- Binary classification of deliveries (Fast vs Delayed)
- Evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix
  - ROC Curve

### Phase 4: Model Evaluation & Comparison
- Performance comparison between regression and classification models
- Visualization of confusion matrices and ROC curves

### Phase 5: Reporting & Insights
- Interpretation of results
- Identification of key factors affecting delivery delays
- Operational recommendations for optimization

---

## Project Structure
```text
food-delivery-time-prediction/
│
├── data/        # Raw and processed datasets
├── notebooks/   # EDA, feature engineering, modeling notebooks
├── visuals/     # Plots and visual outputs
├── reports/     # Final report and summaries
│
├── requirements.txt  # Project dependencies
├── .gitignore        # Ignored files and folders
└── README.md         # Project documentation
```

---

## Tools & Technologies
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Evaluation Metrics
### Regression
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

### Classification
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Final Deliverables
- Jupyter notebooks covering preprocessing, modeling, and evaluation
- Data visualizations (scatter plots, pair plots, confusion matrices, ROC curves)
- Trained regression and classification models
- Final report summarizing:
  - Dataset and preprocessing steps
  - Model performance and comparisons
  - Actionable insights and recommendations

---

## Actionable Insights
Based on model predictions, this project explores improvements such as:
- Optimizing delivery routes
- Adjusting staffing during high-traffic periods
- Improving training strategies for delivery personnel

---

## Future Improvements
- Advanced regression models (Random Forest, Gradient Boosting)
- Hyperparameter tuning
- Model deployment for real-time prediction
- Integration with live delivery systems

---

## Author
- Tamanna Rath
- Machine Learning Assignment Project
