# Credit Risk Analysis
## Overview
The purpose of this analsysis is to compare six different machine learning models and evaluate with method should be used to help predict credit risk. 

## Results
### Naive Random Oversampling
* The Naive Random Oversampling model had a Balanced Accuracy Score of 63.5%.
* Its high-risk precision score is 1%, with a recall score of 59%.
* Its low-risk precision score is 100%, with a recall score of 68%

![image](https://user-images.githubusercontent.com/86032451/138624119-bde5f540-0c79-4f7e-b9b5-8c0369e8394f.png)
![image](https://user-images.githubusercontent.com/86032451/138624143-72fb5d21-421d-43ea-becb-9954a2cdc87e.png)
![image](https://user-images.githubusercontent.com/86032451/138624201-d15fdbe3-9cc1-4442-944f-2b0c88836c8d.png)

### SMOTE Oversampling
* The SMOTE Oversampling model had a Balanced Accuracy Score of 63.4%.
* Its high-risk precision score is 1%, with a recall score of 64%.
* Its low-risk precision score is 100%, with a recall score of 62%.

![image](https://user-images.githubusercontent.com/86032451/138624361-533a2453-9224-494b-a378-ee8a3df3a7b7.png)
![image](https://user-images.githubusercontent.com/86032451/138624368-01183f03-583f-40da-a66d-0c01cb8f9234.png)
![image](https://user-images.githubusercontent.com/86032451/138624378-a77a4fc9-5ec1-482f-ad48-c1fe00f85b80.png)

### Undersampling
* The Undersampling model had a Balanced Accuracy Score of 52.9%
* Its high-risk precision score is 1%, with a recall score of 61%.
* Its low-risk precision score is 100%, with a recall score of 45%

![image](https://user-images.githubusercontent.com/86032451/138624511-9039c7b3-e158-49b2-a1ed-47fb43d0efcd.png)
![image](https://user-images.githubusercontent.com/86032451/138625039-367b757c-ad6e-48a6-9fa1-9105a54be4bc.png)
![image](https://user-images.githubusercontent.com/86032451/138625050-a9532cb4-93b4-4bf9-a4da-4249e2866176.png)

### Combination (Over and Under) Sampling
* The Combination Sampling model had a Balanced Accuracy Score of 62%
* Its high-risk precision score was 1%, with a recall score of 67%
* Its low-risk precision score was 100%, with a recall score of 57%

![image](https://user-images.githubusercontent.com/86032451/138625281-f0465271-0c25-4188-878e-1516b10299cb.png)
![image](https://user-images.githubusercontent.com/86032451/138625296-3d7f8e1a-dd85-4b04-a2f1-8197e89202de.png)
![image](https://user-images.githubusercontent.com/86032451/138625310-259444cb-299f-4137-bba9-df7a27688ca6.png)

### Balanced Random Forest Classifier
* The Balanced Random Forest Classifier model had a balanced accuracy score of 78.78%
* Its high-risk precision score was 4%, with a recall score of 67%
* Its low-risk precision score was 100%, with a recall score of 91%

![image](https://user-images.githubusercontent.com/86032451/138625474-528b64f0-5e75-4d82-afb3-df051e7f9de5.png)
![image](https://user-images.githubusercontent.com/86032451/138625485-636800c4-2aa3-4e66-8c0e-3b635336229c.png)
![image](https://user-images.githubusercontent.com/86032451/138625500-00a47825-6a98-4e63-8a2f-c6941da70292.png)

### Easy Ensemble AdaBoost Classifier
* The Easy Ensemble AdaBoost Classifier model had a balanced accuracy score of 92.54%
* Its high-risk precision score was 7%, with a recall score of 91%.
* Its low-risk precision score was 100%, with a recall score of 94%.

![image](https://user-images.githubusercontent.com/86032451/138625610-da6e8838-7261-45bd-afb7-7e7463b3d868.png)
![image](https://user-images.githubusercontent.com/86032451/138625624-b3e182d9-2094-4dde-8885-b64d95e685f5.png)
![image](https://user-images.githubusercontent.com/86032451/138625637-76857c5c-c2f2-4250-9fa0-0c2eb3a4190d.png)

## Summary
While all models had a low high-risk precision score, the Ensemble models had slightly higher precision scores for that category, with the EasyEnsemble having the highest preciison score at 7%, with a recall score of 92%. This will be the ideal model to choose if a choice had to be made; however, the low precision score still means that some low-risk credit scores can be still falsely classified as high-risk ones, and therefore banks could lose out on certain business opportunities that way. Therefore, I wouldn't advise the client to choose any of the above models. 

