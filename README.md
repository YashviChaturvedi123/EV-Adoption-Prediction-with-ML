Electric Vehicle Adoption Prediction Using Machine Learning
This project uses various machine learning algorithms to predict the likelihood of electric vehicle (EV) adoption based on features such as electric range, battery capacity, government incentives, vehicle type, and manufacturer. The goal is to compare model performance and interpretability to identify the most effective method.

Project Overview
The objective is to analyze and classify EV adoption behavior using a synthetic dataset that simulates real-world adoption conditions. Multiple models were trained, evaluated, and compared using standard performance metrics.

Technologies and Libraries
Python

Pandas, NumPy

scikit-learn

Matplotlib, Seaborn

Dataset Description
A synthetic dataset with 500 samples was generated, including the following features:

Year: Year of vehicle registration

State: Encoded US state

Make: Encoded vehicle manufacturer

ElectricRange: Estimated electric range (miles)

BatteryCapacity: Battery size (kWh)

IncentiveAmount: Government incentive (USD)

EVType: Encoded as BEV (Battery Electric Vehicle) or PHEV (Plug-in Hybrid Electric Vehicle)

Adopted: Target variable (1 = Adopted, 0 = Not Adopted)

Models Implemented
Model	Description
Naive Bayes	Fast, probabilistic classifier providing a reliable baseline
Random Forest	Ensemble-based method, offered the highest accuracy
K-Nearest Neighbors (KNN)	Compared users based on feature similarity
Artificial Neural Network (ANN)	Captured non-linear relationships in the data

Evaluation Metrics
Accuracy Score

Confusion Matrix

Classification Report

ROC Curve and AUC Score

Accuracy Comparison Bar Chart

Results Summary
Random Forest emerged as the most accurate and well-balanced model.

ANN showed strong learning capabilities for non-linear patterns but required more resources.

All models were evaluated using ROC curves and classification metrics.

Visualizations
ROC curves for each model to compare classification performance

Accuracy bar chart showing model performance side-by-side

How to Run:-
Clone the repository:

1.bash:-
git clone https://github.com/your-username/ev-adoption-ml.git
cd ev-adoption-ml
Install required libraries:

2.bash:-
pip install -r requirements.txt
Open the Jupyter Notebook:
Run ev_adoption_prediction.ipynb using Jupyter Notebook or any compatible IDE.

