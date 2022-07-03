# Credit Risk Analysis

## Overview
In this project, I applied supervised machine learning to a credit card credit dataset from LendingClub to predict credit risk.

The following models were used in the technical analyses:
  - RandomOverSampler, SMOTE, and ClusterCentroids
  - SMOTEENN
  - BalancedRandomForestClassifier and EasyEnsembleClassifier
  
## Results
### Naive Random Oversampling
<img width="453" alt="Screen Shot 2022-07-02 at 4 17 54 PM" src="https://user-images.githubusercontent.com/100643519/177043842-a879a374-63ef-4298-b83c-9c1b5fc97f28.png">

  - The balanced accuracy score was 63%.
  
  <img width="721" alt="Screen Shot 2022-07-02 at 4 18 18 PM" src="https://user-images.githubusercontent.com/100643519/177016422-df1236c8-147d-4c3b-a7dc-380fa980e45f.png">
  
  - The precision for high-risk was 1% and the precision for low-risk was 100%.
  - The recall for high-risk was 61% and the recall for low-risk was 66%.
  
### SMOTE Oversampling
<img width="362" alt="Screen Shot 2022-07-02 at 4 19 55 PM" src="https://user-images.githubusercontent.com/100643519/177016451-3be5be0f-bd32-4723-a0f7-79c4c40bdaaa.png">
<img width="724" alt="Screen Shot 2022-07-02 at 4 20 09 PM" src="https://user-images.githubusercontent.com/100643519/177016453-7b4b4c0c-3473-42e2-a3cd-4457d06e91c5.png">

### Undersampling
<img width="351" alt="Screen Shot 2022-07-02 at 4 29 56 PM" src="https://user-images.githubusercontent.com/100643519/177016666-ea3b965c-92cf-4ac7-b86d-18f93b4b8936.png">
<img width="717" alt="Screen Shot 2022-07-02 at 4 30 09 PM" src="https://user-images.githubusercontent.com/100643519/177016668-f632e4a3-5727-42d7-8c7a-1f0b4306f36f.png">

### SMOTEENN
<img width="352" alt="Screen Shot 2022-07-02 at 4 34 53 PM" src="https://user-images.githubusercontent.com/100643519/177016779-66c36aec-fb01-4f6a-b09b-6c47bfd05ab6.png">
<img width="721" alt="Screen Shot 2022-07-02 at 4 35 06 PM" src="https://user-images.githubusercontent.com/100643519/177016895-789f4a05-1251-435d-acaf-229f141d9d58.png">
                                                                 
### Balanced Random Forest Classifier
<img width="354" alt="Screen Shot 2022-07-02 at 4 37 17 PM" src="https://user-images.githubusercontent.com/100643519/177016827-efb6f6bc-8013-4e19-8b27-083d1adaa284.png">
<img width="719" alt="Screen Shot 2022-07-02 at 4 37 28 PM" src="https://user-images.githubusercontent.com/100643519/177016829-ef7f9a76-4403-499f-b9be-1186e5b20484.png">
                                                                 
### Easy Ensemble AdaBost Classifier
<img width="351" alt="Screen Shot 2022-07-02 at 4 39 51 PM" src="https://user-images.githubusercontent.com/100643519/177016870-0fcb743f-2233-4c77-968a-77091a8ef1be.png">
<img width="721" alt="Screen Shot 2022-07-02 at 4 40 07 PM" src="https://user-images.githubusercontent.com/100643519/177016873-36df67c3-dcd2-411e-a36d-8974d7c16203.png">
                                                                 
