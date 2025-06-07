# HR Analytics – Employee Attrition Prediction

This project uses machine learning and visualization tools to analyze the factors behind employee attrition and predict future resignations.


## Objective
Use HR data to:
- Analyze key drivers of employee attrition
- Build a classification model to predict attrition
- Explain model decisions using SHAP
- Create actionable HR prevention strategies
- Visualize insights with Power BI



##  Tools & Technologies
- Python (Pandas, Seaborn, Scikit-learn)
- SHAP (Explainable ML)
- Power BI (Visualization)
- Google Colab



##  Project Structure
```
HR_Analytics_Attrition_Prediction/
├── hr_data.ipynb                      # Python notebook with EDA, model & SHAP
├── pdf_reports/
│   ├── Model_Accuracy_Report.pdf
│   └── Attrition_Prevention_Strategy.pdf
├── visualization_csvs/               # Power BI-ready CSV exports
│   ├── dept_attrition.csv
│   ├── role_attrition.csv
│   ├── salary_attrition.csv
│   ├── overtime_attrition.csv
│   ├── gender_attrition.csv
│   └── promotion_attrition.csv
├── powerbi/
│   └── dashboard_screenshot.png
├── README.md
```



##  Deliverables
- ✅ Machine learning model with 85% accuracy
- ✅ Confusion matrix & classification report
- ✅ SHAP-based feature importance
- ✅ Power BI dashboard with filters & charts
- ✅ PDF with prevention strategy suggestions



##  How to Use
1. Clone the repo
2. Open hr_data.ipynb in Jupyter or Colab
3. Run cells to reproduce model & SHAP analysis
4. Open CSV files in Power BI to recreate dashboard



##  Insights Example
- Employees with >4 years in same role are at higher risk
- Lack of promotion, low work-life balance strongly predict attrition
- OverTime is a key SHAP feature



