# Credit Risk Analysis

## Overview
In this project, I applied supervised machine learning to a credit card credit dataset from LendingClub to predict credit risk.

The following models were used in the technical analyses:
  - RandomOverSampler, SMOTE, and ClusterCentroids
  - SMOTEENN
  - BalancedRandomForestClassifier and EasyEnsembleClassifier
  
## Results
### Naive Random Oversampling
  - The balanced accuracy score was 63%.  
  - The precision for high-risk was 1% and the precision for low-risk was 100%.
  - The recall for high-risk was 61% and the recall for low-risk was 66%.
<img width="453" alt="Screen Shot 2022-07-02 at 4 17 54 PM" src="https://user-images.githubusercontent.com/100643519/177046645-26df3fd6-c92d-41a6-a77b-8d87097188fa.png">
<img width="721" alt="Screen Shot 2022-07-02 at 4 18 18 PM" src="https://user-images.githubusercontent.com/100643519/177046659-34d39b36-40e3-428e-870f-9a77cc1322a1.png">

### SMOTE Oversampling
  - The balanced accuracy score was 66%.
  - The precision for high-risk was 1% and the precision for low-risk was 100%.
  - The recall for high-risk was 63% and the recall for low-risk was 68%.
<img width="362" alt="Screen Shot 2022-07-02 at 4 19 55 PM" src="https://user-images.githubusercontent.com/100643519/177016451-3be5be0f-bd32-4723-a0f7-79c4c40bdaaa.png">
<img width="724" alt="Screen Shot 2022-07-02 at 4 20 09 PM" src="https://user-images.githubusercontent.com/100643519/177016453-7b4b4c0c-3473-42e2-a3cd-4457d06e91c5.png">

### Undersampling
  - The balanced accuracy score was 54%.
  - The precision for high-risk was 1% and the precision for low-risk was 100%.
  - The recall for high-risk was 69% and the recall for low-risk was 40%.
<img width="351" alt="Screen Shot 2022-07-02 at 4 29 56 PM" src="https://user-images.githubusercontent.com/100643519/177016666-ea3b965c-92cf-4ac7-b86d-18f93b4b8936.png">
<img width="717" alt="Screen Shot 2022-07-02 at 4 30 09 PM" src="https://user-images.githubusercontent.com/100643519/177016668-f632e4a3-5727-42d7-8c7a-1f0b4306f36f.png">

### SMOTEENN
  - The balanced accuracy score was 69%.
  - The precision for high-risk was 1% and the precision for low-risk was 100%.
  - The recall for high-risk was 79% and the recall for low-risk was 58%.
<img width="352" alt="Screen Shot 2022-07-02 at 4 34 53 PM" src="https://user-images.githubusercontent.com/100643519/177016779-66c36aec-fb01-4f6a-b09b-6c47bfd05ab6.png">
<img width="721" alt="Screen Shot 2022-07-02 at 4 35 06 PM" src="https://user-images.githubusercontent.com/100643519/177016895-789f4a05-1251-435d-acaf-229f141d9d58.png">
                                                                 
### Balanced Random Forest Classifier
  - The balanced accuracy score was 79%.
  - The precision for high-risk was 3% and the precision for low-risk was 100%.
  - The recall for high-risk was 70% and the recall for low-risk was 87%.
<img width="354" alt="Screen Shot 2022-07-02 at 4 37 17 PM" src="https://user-images.githubusercontent.com/100643519/177016827-efb6f6bc-8013-4e19-8b27-083d1adaa284.png">
<img width="719" alt="Screen Shot 2022-07-02 at 4 37 28 PM" src="https://user-images.githubusercontent.com/100643519/177016829-ef7f9a76-4403-499f-b9be-1186e5b20484.png">
                                                                 
### Easy Ensemble AdaBost Classifier
  - The balanced accuracy score was 93%.
  - The precision for high-risk was 9% and the precision for low-risk was 100%.
  - The recall for high-risk was 92% and the recall for low-risk was 94%.
<img width="351" alt="Screen Shot 2022-07-02 at 4 39 51 PM" src="https://user-images.githubusercontent.com/100643519/177016870-0fcb743f-2233-4c77-968a-77091a8ef1be.png">
<img width="721" alt="Screen Shot 2022-07-02 at 4 40 07 PM" src="https://user-images.githubusercontent.com/100643519/177016873-36df67c3-dcd2-411e-a36d-8974d7c16203.png">

## Summary
In all the models I used, the precision measures for high-risk credit applicants were very low. This means that there is a high chance of false positives. False positives are not a big concern, because there is no negative affect on credit companies for falsely denying low-risk applicants. The recall is a more important metric in detecting credit risk because we are more concerned with false negatives. A low recall measure would mean that our model is more likely to predict that someone is not going to default, but they do. Given this information, I would recommend the use of the Easy Ensemble Classifier model because the recall measure for high-risk applicants was 94%.
