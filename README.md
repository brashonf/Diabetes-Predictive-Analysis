# Predicting Diabetes-Related Hospital Readmissions

## Objective  
Predict hospital readmissions within 30 days to improve healthcare decision-making and reduce costs.

## Dataset  
[Diabetes 130-US Hospitals](https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008)

## Key Features  
- **Age, Gender, Race**
- **Admission Type**
- **Medication Changes**
- **Lab Results (e.g., HbA1c)**

## Approach  
1. **Exploratory Data Analysis**: Identified trends and key features.  
2. **Risk Adjustment**: Used propensity scores for matching.  
3. **Machine Learning**: Trained a Random Forest model to predict readmissions.  

## Results  
- **Accuracy**:  
- **Precision**:  
- **Key Insight**: Patients with medication changes are X% more likely to be readmitted.

## Visualizations  
- [Insert plots here]

## Tools  
Python, scikit-learn, SHAP, matplotlib, pandas.

## How to Run  
1. Clone this repository.  
2. Install dependencies: `pip install -r requirements.txt`.  
3. Run the notebook: `jupyter notebook diabetes_analysis.ipynb`.  
