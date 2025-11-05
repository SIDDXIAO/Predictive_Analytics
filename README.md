📘 Course: Predictive Analytics (BCADS1501)
Babu Banarasi Das University, Lucknow
Semester: 5th
Submitted By: Siddhant Kumar Patel (BCA DS 36)
Submitted To: Mr. Ayushman Bhadauria

📂 Project Overview
This project focuses on applying Predictive Analytics techniques using IBM SPSS Modeler to analyze customer response data for the company ACME, which sells sports products.

The objective was to predict customer behavior and identify potential buyers for a new product — the XL Original Orange Baseball Cap — using machine learning models.

🎯 Objective
To build a predictive model that estimates whether a customer will respond positively to a promotional campaign. The task involves applying classification algorithms within IBM SPSS Modeler and understanding the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework.

🧩 Tools & Technologies
IBM SPSS Modeler (Primary tool – visual, no-code machine learning)
ACME Dataset (30,000 records, 12 columns)
Data Mining Techniques:
CHAID Decision Tree
Data Filtering, Auditing, and Preprocessing
Model Evaluation (Gain Chart, Accuracy, Probability Fields)
🧠 Learning Outcomes
Understanding of predictive modeling workflow in SPSS Modeler.
Skills in data preprocessing, variable setting, and missing value handling.
Ability to train and test predictive models effectively.
Evaluation using metrics such as accuracy, R², RMSE, and gain charts.
Familiarity with the CRISP-DM process for structured data mining.
⚙️ Process Workflow
Import Dataset: 30,000 rows × 12 columns.
Filter Training Data: Select "YES" responses for training.
Build Model: Use CHAID algorithm to train.
Filter Test Data: Select "NO" responses for testing.
Evaluate Model: Connect the model with test data and analyze predictions.
Generate New Fields:
$R-response_to_test_mailing_02_01_2011 → Predicted True/False
$RC-response_to_test_mailing_02_01_2011 → Probability score
Export Results: Filter and save customers predicted to buy (True).
