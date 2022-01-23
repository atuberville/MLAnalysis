# Credit Risk
The purpose of this analysis was to determine which machine learning technique is more accurate when determining credit risk. We then train these models and determine how accurate they are by reviewing test data. 

# Sample Methods
•	Naïve Random Oversampling
 ![image](https://user-images.githubusercontent.com/89363928/150664308-f52741f9-df53-4e38-94b8-b5659dd3279a.png)

•	SMOTE Oversampling
 ![image](https://user-images.githubusercontent.com/89363928/150664311-df68253b-5e76-4f2b-b64e-7fd2a79fe736.png)

•	Undersampling
 ![image](https://user-images.githubusercontent.com/89363928/150664312-72ebe18e-4faa-4dc7-950c-5b9cdfc6bc73.png)

•	Combination Sampling
 ![image](https://user-images.githubusercontent.com/89363928/150664316-74a4a6bb-9c31-44e5-96df-1526d71851c7.png)

•	Balanced Random Forest
 ![image](https://user-images.githubusercontent.com/89363928/150664324-5733f0c0-43db-412b-95e0-038eaf7cbb8f.png)

The first three options of Random Oversampler, Smote, and Undersampling how the lowest gap between predicted high risk and predicted low risk. The model was essentially saying that there was an even chance between the creditors riskiness. Based on that information I felt that these three were not good options for this analysis. Sensitivity metrics for under sampling and combination sampling were less than 60% however, I wouldn’t consider this to be a strength or a weakness of the model seeing as there are several factors that cannot be categorized when it comes to analyzing people.

# Summary
The balanced random forest method had the highest degree of accuracy at 93% however, none of these models can effectively predict credit risk because there are other factors involved that cannot be factored into the model. These things include new earning potential from a recent college graduate, potential loyalty gains from taking a chance on a borrower that  has medium risk etc.
