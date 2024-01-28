# DataScience
# Project :: Rainfall-Prediction-END-END

Overall look of front-end
we have used HTML, CSS, BOOTSTRAP, FLASK

![1](https://user-images.githubusercontent.com/77119829/136656390-c5717bbc-0472-4b94-98ce-1cff353e9424.PNG)
![2](https://user-images.githubusercontent.com/77119829/136656397-b4b7d58c-9339-4474-a3c5-48857825afd9.PNG)

![3](https://user-images.githubusercontent.com/77119829/136656323-e71577be-c354-4fad-ad93-93760b7a53e0.PNG)

we have deployed our mahine learning model.

As the project is about the rainfall prediction in australia. We have got set of features we did our data analysis through this we achived some important insights.

![6](https://user-images.githubusercontent.com/77119829/136656940-c3b16e86-85dc-4812-a280-933b8719516e.PNG)
![7](https://user-images.githubusercontent.com/77119829/136656941-18ac6f1d-4c34-4ed1-9d85-000905a23d5f.PNG)
![4](https://user-images.githubusercontent.com/77119829/136656942-f285cd43-9e9f-455a-869a-29338e521c37.PNG)
![5](https://user-images.githubusercontent.com/77119829/136656944-3c9178de-c238-4570-8997-fa3ac3647700.PNG)


The we performed our feature engineering where we dealt with the nan values, most importantly outliers and dealt categorical variables by encoding. 
![ou1](https://user-images.githubusercontent.com/77119829/136656948-730cd6d9-4252-4f91-80bb-1f9ea298c1d2.PNG)
![ou2](https://user-images.githubusercontent.com/77119829/136656950-6f4746ed-7a06-47c9-bb30-96118a68650b.PNG)


We also applied the log normal distribution to standardize our continuous features.

As we have got alot of features so we did feature selection to select only those features which were very important.

We used RandomForest classifier and we achived 83 percent accuracy and most importantly we dealt with data leakage as well.
We also analyzed our predictions using appropriate metrics.

We also tried the artifical neuron network (ANN) where we achived 79 percent accuracy.

# Project :: Mobile Price Prediction System
## Project Description
Bob, the visionary founder of a burgeoning mobile company, recognizes the fierce competition in the market and understands the pivotal role data science plays in gaining a competitive edge. In an effort to strategically position his products, Bob has initiated a Mobile Price Prediction System. This sophisticated system analyzes diverse features of mobile phones to predict their price range, enabling Bob's company to offer competitive products against industry giants like Apple and Samsung
# Project Steps:
## 1) Data Collection:
Gather a comprehensive dataset containing diverse features of mobile phones, including specifications, features, and pricing information.

## 2) Data Exploration and Analysis:
Conduct in-depth data analysis using various visualization techniques such as 📊 pie charts, 📈 bar graphs, 📊 histograms, and 📊 box-whisker plots.
Uncover insights related to the correlation between mobile phone features and pricing.

<p align="center">
  <img src="Mobile Price Prediction Images/graph-1.png" alt="graph-1">
</p>
<p align="center">
  <img src="Mobile Price Prediction Images/graph-2.png" alt="graph-2">
</p>
<p align="center">
  <img src="Mobile Price Prediction Images/graph-3.png" alt="graph-3">
</p>
<p align="center">
  <img src="Mobile Price Prediction Images/graph-4.png" alt="graph-4">
</p>
<p align="center">
  <img src="Mobile Price Prediction Images/graph-5.png" alt="graph-5">
</p>

<p align="center">
  <img src="Mobile Price Prediction Images/graph-7.png" alt="graph-7">
</p>
<p align="center">
  <img src="Mobile Price Prediction Images/graph-8.png" alt="graph-8">
</p>


## 3) Feature Engineering:
Subsequently, rigorous feature engineering was undertaken to enhance the robustness of the dataset
### Log-Normal Distribution:
Incorporated a log-normal distribution to transform relevant features, ensuring a more normalized and representative distribution for model training.
### Handling Missing Data:
Addressed missing data points using appropriate strategies, such as imputation or removal, to ensure a complete and informative dataset.
### Outlier Removal:
Strategically removed non-informative outliers to improve the model's accuracy and reliability. This step involved careful consideration of the impact of outliers on the predictive performance.

<p align="center">
  <img src="Mobile Price Prediction Images/graph-6.png" alt="graph-6">
</p>
<p align="center">
  <img src="Mobile Price Prediction Images/graph-7.png" alt="graph-7">
</p>
<p align="center">
  <img src="Mobile Price Prediction Images/graph-8.png" alt="graph-8">
</p>

## 4) Feature Selection:
Feature selection was a crucial step in optimizing the model's performance:
### Correlation Analysis:
- Leveraged correlation analysis to identify and retain only the most influential features.
- Removed redundant or highly correlated features to streamline the dataset for optimal predictive accuracy.
<p align="center">
  <img src="Mobile Price Prediction Images/graph-9.png" alt="graph-9">
</p>
  

## 5) Model Training:
The final step involved training a RandomForestClassifier model with the refined dataset:
### Model Type:
Implemented a RandomForestClassifier, a robust ensemble learning model known for its effectiveness in classification tasks.
### Training Accuracy:
Achieved an impressive accuracy of 92.75% during the training phase, showcasing the model's capability to learn and generalize from the dataset.
### Classification Report:
The model's classification report provides detailed metrics:
- Precision: Indicates the accuracy of positive predictions.
- Recall: Measures the model's ability to capture all relevant instances.
- F1-score: Harmonic mean of precision and recall, offering a balanced assessment.

<p align="center">
  <img src="Mobile Price Prediction Images/graph-10.png" alt="graph-10">
</p> 

## 6) Model Evaluation:
Evaluate the trained model's performance using metrics such as precision, recall, and F1-score.
Analyze the model's effectiveness in categorizing mobile phones into distinct price ranges.

 
