# IEEE-CIS Fraud Detection
ეს პროექტი ეხება Kaggle-ის [IEEE-CIS Fraud Detection](https://www.kaggle.com/competitions/ieee-fraud-detection) კონკურსს. მიზანია განისაზღვროს არის თუ არა ტრანზაქცია თაღლითური, ~590,000 ტრანზაქციისა და 400+ ფიჩერის მონაცემთა ბაზის გამოყენებით. ყველა ექსპერიმენტი დალოგილია MLflow-ზე DagsHub-ის მეშვეობით.

## რეპოზიტორიის სტრუქტურა
ML_assignment2/
├── model_xgboost.ipynb                  - XGBoost ექსპერიმენტები + ჰიპერპარამეტრების ტუნინგი
├── model_random_forest.ipynb            - Random Forest ექსპერიმენტები + ჰიპერპარამეტრების ტუნინგი
├── model_logistic_regression.ipynb      - Logistic Regression ექსპერიმენტები
├── model_inference.ipynb                - საბოლოო მოდელის inference + submission.csv-ის დაგენერირება
