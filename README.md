# Credit_Risk_Analysis
## Purpose
The purpose of this analysis was to predict credit risk with a variety of different machine learning models that we built and evaluated using Python. After evaluating the performance of the models, we will compare the models to see which particular model would be the most successful and trustwrothy to predict credit cark risk.
## Results
**Naive Random Oversampling**

![76D0304A-382C-49C6-BF5C-E244A0CC6D47_4_5005_c](https://user-images.githubusercontent.com/92240407/165017167-74785b55-762a-4e09-ae3b-90ff139ab0cf.jpeg)

- Balanced Accuracy Score: 64%
- Percision: The percision for high risk loans is low while the percision for low risk loans is high.
- Recall: The recall for high risk loans is 66% and for low risk loans recall is 62%.

**SMOTE Oversampling**

![CB556273-FBD3-498A-9256-4E4E3FE748F8_4_5005_c](https://user-images.githubusercontent.com/92240407/165017635-5cca2ae1-9db1-4050-a2f3-60805acbefd4.jpeg)

- Balanced Accuracy Score: 65%
- Percision: The percision for high risks loans is low while the percision for low risk loans is high.
- Recall: The recall for high risk loans is 61% and for low risk loans recall is 69%.

**Undersampling**

![26608B02-3F4C-464B-ABF1-7D0AF6D4EC06_4_5005_c](https://user-images.githubusercontent.com/92240407/165017828-71fa4b9a-44ba-40a0-a3b8-114760e7385a.jpeg)

- Balanced Accuracy Score: 54%
- Percision: The percission for high risk loans is low while the percision for low risk loans is high.
- Recall: The recall for high risk loans is 69% and for low risk loans recall is 40%.

**Combination (Over and Under) Sampling**

![9C78F269-DEC9-4559-A49B-A626946A554B_4_5005_c](https://user-images.githubusercontent.com/92240407/165018037-87be2684-c97a-425e-8dd8-638eae358ed1.jpeg)

- Balanced Accuracy Score: 66%
- Percission: The percission for high risk loans is low while the percision for low risk loans is high.
- Recall: The recall for high risk loans is 75% and for low risk loans recall is 56%.

**Balanced Random Forest Classifier**

![CB10E5B3-9064-466C-8087-E3F7D1E9718E_4_5005_c](https://user-images.githubusercontent.com/92240407/165018250-0679209e-eff2-486a-8078-15fc7b7a1948.jpeg)

- Balanced Accuracy Score: 79%
- Percission: The percission for high risk loans is low while the percision for low risk loans is high.
- Recall: The recall for high risk loans is 70% and for low risk loans recall is 87%.

**Easy Ensemble AdaBoost Classifier**

![C3A987E5-2E02-4025-A338-B1F7743614AA_4_5005_c](https://user-images.githubusercontent.com/92240407/165018466-6ed4b75a-bccb-42cc-a424-27f97f82b38a.jpeg)

- Balanced Accuracy Score: 93%
- Percission: The percission for high risk loans is low while the percision for low risk loans is high.
- Recall: The recall for high risk loans is 92% and for low risk loans the recall is 94%.

## Summary
In regards to balanced accuracy, the highest compared accuracy between 0 and 1 and that has a score closest to 1 will yield the best machine learning model. Between all the machine learning models we created in this challenge, the Easy Ensemble AdaBoost Classifier would be the best model to choose as it received a balanced accuracy of about 93%. The other machine learning models we created only received a balanced accuracy score of about 79% and below. The recall rates for this specific model also were the closest to 1 indicating that the Easy Ensemble AdaBoost classifier would be the best model to choose for detecting credit risk. The percission rates for all of the 6 models we created were around the same and were deemed appropriate for the range. Due to all of these factors, the Easy Ensemble AdaBoost Classifier proves to be the most useful and trustworthy model! 
