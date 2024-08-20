# Machine Learning Project: Predicting Customer No-Shows

## Project Overview
This project was developed to address the critical issue of customer no-shows at CouponSavvy, a company specializing in distributing coupons for various services. The high rate of no-shows has been causing significant financial losses for merchants. Our goal is to build a machine learning model that predicts the likelihood of a customer failing to honor their reservation, enabling CouponSavvy to take proactive measures to minimize these occurrences.

## Exploratory Data Analysis (EDA)
The EDA revealed key insights:
- Web-based voucher purchases are more common than mobile transactions.
- The no-show rate is significant, with approximately 33.13% of customers not showing up for their reservations.
- Consumer preferences lean towards Japanese and traditional Portuguese cuisines, as well as beauty and spa services.
- Variability in pricing for identical services within the same category suggests a strategic use of differentiated pricing.

## Modelling
We employed several machine learning models to predict customer no-shows, including:
- XGBoost
- Decision Tree
- Random Forest
- Neural Network

## Model Evaluation
The models were evaluated based on accuracy, recall, precision, and AUC. Recall was particularly important due to the high cost of false negatives (predicting that a customer will show up when they actually won't).

### Results
- XGBoost: Balanced performance with 80.13% accuracy and 64.2% recall.
- Decision Tree: Highest recall at 77.17%, but lower accuracy (68.13%).
- Random Forest: Best precision (78.2%) but lower recall (57.19%).
- Neural Network: Optimal model with 75% accuracy and a good balance between recall (68%) and precision.

## Conclusion and Recommendations
The Neural Network model was selected as the optimal solution for predicting customer no-shows. It effectively balances accuracy and recall, minimizing the financial impact on merchants. We recommend implementing the Neural Network model and enhancing it with up-to-date data. Additionally, specific strategies such as deposit requirements for high-demand services and data-informed compensation models for merchants are advised to further reduce no-shows.
