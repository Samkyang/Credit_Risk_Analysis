# Credit_Risk_Analysis

Overview of the loan prediction risk analysis:
I used machine learning in that was covered in this module to create a way to screen loan candidates with greater accuracy so that they don't default on their loans.


Results:
### Naive Random Oversampling
![image](https://user-images.githubusercontent.com/92561003/155026816-ef773f4b-d7eb-4bc6-8947-e475fda0c042.png)

### SMOTE Oversampling
![image](https://user-images.githubusercontent.com/92561003/155026852-6c1495dc-4e24-4e7b-b5bd-e4a53e577081.png)

### Cluster Centroid Undersampling
![image](https://user-images.githubusercontent.com/92561003/155026924-2329dc8d-a1eb-475a-b239-2db9a6a0ff87.png)

### SMOTEENN
![image](https://user-images.githubusercontent.com/92561003/155026981-821c4b4c-a1ee-4ddf-b8a2-8ab3f61922f7.png)

### Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/92561003/155027060-7b4a51cb-0b4a-4899-8a70-91f0069356d8.png)

### Easy Ensemble AdaBoost Classifier
![image](https://user-images.githubusercontent.com/92561003/155027099-c94f7efa-1aab-449c-8e5a-7b4014be8ea6.png)

## Summary:
Sensitivity is valued more than precision when it comes to banks issuing loans because it decreases the chance a customer will default on a loan. Each one of the methods had really low precision for high risk applicants and high precision for low risk applicants. Easy Ensemble AdaBoost Classifier had the highest precision when it came to high risk customers.
Moving on to the next qualifier would be to look at the sensitivity. Easy Ensemble AdaBoost Classifier scored the highest again in both high and low risk categories followed by Balanced Random Forest Classifier.
The final part to look at is the balanced accuracy score one which model to use. Easy Ensemble AdaBoost Classifier scored the highest again in this category so this is the one I would go with since it is the more accurate, precice and most sensitive.
