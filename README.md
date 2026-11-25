# Diabetes Risk Prediction and Performance Analysis

Data Analytics mini-project: Logistic Regression classification using the Early Stage Diabetes Risk Prediction dataset.

## Workflow
- Data loading and inspection
- Duplicate removal and categorical encoding
- Exploratory data analysis
- Stratified train/test split (80/20)
- Logistic Regression model
- Evaluation with Accuracy, Precision, Recall, F1-score and confusion matrix

## Included
- `Diabetes_Risk_Prediction_Analytics.ipynb`: notebook
- `project_report.txt`: report
- `model_performance.csv`: evaluation values
- `visualizations/`: PNG charts
- `dataset/GET_DATASET.txt`: how to obtain CSV

## Dataset
Official UCI page: https://archive.ics.uci.edu/dataset/529/early+stage+diabetes+risk+prediction+dataset
Download `diabetes_data_upload.csv` and add it to `dataset/`. The notebook upload cell also prompts you to select the CSV.

## Results reported in the uploaded notebook
Accuracy 82.35%, Precision 93.33%, Recall 80.00%, F1-score 86.15%.
Confusion matrix: TN=14, FP=2, FN=7, TP=28.

## Important limitation
The saved notebook run dropped duplicates and reduced 520 records to 251. This should be reviewed and justified before presenting the results. Educational only, not a clinical diagnostic model.
