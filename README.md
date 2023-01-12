# An Efficient Ensemble Stacking Method For Customer Churn Prediction
## What is Customer churn?
- In business, “customer churn” is  one of the most important metrics for a growing business to evaluate.
* Customer churn has many reasons and factors. Such reasons include quality and cost of services.
> Ensemble learning
- Ensemle Learning is technique that craete multiple models and then combine them to produce improved results.
* Ensemble Learning usually produces more accurate solutions than a single model.
+ Ensemble learning methods are applied to regression as well as classifacation.
![image](https://user-images.githubusercontent.com/92161283/212068807-121c0a3c-a367-43c1-86f5-6508a4d48948.png)
## Voting Classifiers
- Voting Classifiers comes with multiple voting options such as hard and soft voting.
+ Hard Voting uses multiple individual models to make its prediction.
*  Soft Voting relies on probabiltistic outcome values genereted by classification algorithms.
  ![image](https://user-images.githubusercontent.com/92161283/212069100-4d640890-aab6-41d1-b01f-609891bf5517.png)

   ![image](https://user-images.githubusercontent.com/92161283/212069149-a5ac3a1d-d5e6-4db7-8f43-30843f904c60.png)
   
## GENERAL OVERVIEW OF THE MODEL
![image](https://user-images.githubusercontent.com/92161283/212069492-40021e56-2cd6-4ee0-8e51-4cdac06e5b7e.png)
     
## Proposed an efficient stacking ensemble method for customer churn prediction 
![image](https://user-images.githubusercontent.com/92161283/212069665-ce0f3160-6de1-46a3-9fb0-2005d75f4669.png)
> Comparison with other works
![image](https://user-images.githubusercontent.com/92161283/212069794-2ac8119b-38ad-420d-a434-781b3949c60f.png)
> ** Further analysis **
![image](https://user-images.githubusercontent.com/92161283/212069882-a6541680-2932-4bbc-9f83-544319db7f6b.png)

![image](https://user-images.githubusercontent.com/92161283/212069939-72ab62ee-0b72-4012-b4d1-1eb28211ede8.png)

### Conclusion
+ All condidate models were evaluated on a public dataset in the telecom industry.
+ MLP, Random Forest, CatBoost and XGBoost selected for an efficient stacking ensemble method.
+ Created an ensemble model utilizing the soft voting approach.
+ Proposed model showed the best accuracy of 88.2 %  with balanced data.
