The data file diabetes.csv contains data of 768 patients. In this data there are 8 attributes (Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age) and 1 response variable (Outcome). The response variable, Outcome, has binary value (1 indicating the outcome is diabetes and 0 means no diabetes). For this assignment purposes we will consider this data as a population.  
- a) Have set a seed (to ensure work reproducibility) and taken a random sample of 25 observations and then have compared the mean Glucose and highest Glucose values of this sample with the population statistics of the same variable. The analysis is then visualized using bar graphs.
- b) The 98th percentile of BMI of the sample and the population has been analysed and the results been compared using bar graphs.
- c) Using bootstrap (replace= True), created 500 samples (of 150 observation each) from the population and then compared the average mean, standard deviation and percentile for BloodPressure with the population for the same variable. Then visualized the observations using bar charts.
