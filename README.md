# PredictiveModelingForAgriculture
I dived into agriculture using supervised machine learning and feature selection to aid farmers in crop cultivation and solve real-world problems.
Problem Statement
Sowing Success: How Machine Learning Helps Farmers Select the Best Crops
![farmer_in_a_field](https://github.com/RashidTobrazune/PredictiveModelingForAgriculture/assets/150378293/a2853819-e72f-4d57-8870-3758977633b2)


Measuring essential soil metrics such as nitrogen, phosphorous, potassium levels, and pH value is an important aspect of assessing soil condition. However, it can be an expensive and time-consuming process, which can cause farmers to prioritize which metrics to measure based on their budget constraints.

Farmers have various options when it comes to deciding which crop to plant each season. Their primary objective is to maximize the yield of their crops, taking into account different factors. One crucial factor that affects crop growth is the condition of the soil in the field, which can be assessed by measuring basic elements such as nitrogen and potassium levels. Each crop has an ideal soil condition that ensures optimal growth and maximum yield.

A farmer reached out to you as a machine learning expert for assistance in selecting the best crop for his field. They've provided you with a dataset called soil_measures.csv, which contains:

"N": Nitrogen content ratio in the soil
"P": Phosphorous content ratio in the soil
"K": Potassium content ratio in the soil
"pH" value of the soil
"crop": categorical values that contain various crops (target variable).
Each row in this dataset represents various measures of the soil in a particular field. Based on these measurements, the crop specified in the "crop" column is the optimal choice for that field.

In this project, you will build multi-class classification models to predict the type of "crop" and identify the single most importance feature for predictive performance.
Answer these quentions;
Identify the single feature that has the strongest predictive performance for classifying crop types.
Find the feature in the dataset that produces the best score for predicting “crop”.
From this information, create a variable called best_predictive_feature, which:
Should be a dictionary containing the best predictive feature name as a key and the evaluation score (for the metric you chose) as the value.

Analysis and Insights
In multiclass classification problems, the F1 score can be adapted to handle multiple classes by using averaging methods such as:

Macro: Averages the F1 scores for each class without considering class imbalance.
Micro: Aggregates the contributions of all classes to compute the average F1 score.
Weighted: Averages the F1 scores for each class while considering the support (the number of true instances) of each class.

<img width="960" alt="Screenshot 2024-07-09 140114" src="https://github.com/RashidTobrazune/PredictiveModelingForAgriculture/assets/150378293/bbc4284f-b70a-49e1-b459-d573e30005fa">

<img width="960" alt="Screenshot 2024-07-09 140136" src="https://github.com/RashidTobrazune/PredictiveModelingForAgriculture/assets/150378293/1428dcda-e79a-495c-836b-456fe95d80a4">

<img width="960" alt="Screenshot 2024-07-09 140150" src="https://github.com/RashidTobrazune/PredictiveModelingForAgriculture/assets/150378293/366a62b4-5651-4be0-a713-250008ca869c">

<img width="528" alt="agric_results" src="https://github.com/RashidTobrazune/PredictiveModelingForAgriculture/assets/150378293/e10a58c7-b47a-4dc8-a00e-e54f6d33b7db">
