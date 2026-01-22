Home Loan Data Analysis

Overview:
This project focuses on creating a Deep Learning model that predicts whether or not an applicant will be able to repay a loan using the historical data. 
The dataset is highly imbalanced and analysis includes data preprocessing for cleaning the data, performing exploratory data analysis, data imputations and visualization to draw meaningful insights

Tools and Techniques:
Pandas
Numpy
MatplotLib,Seaborn
Scikit-Learn
Keras/Tensors

Dataset information:
The dataset used for this project is approximately 166MB which is more than the permitted limit to upload in GitHub. 
Please find the dataset in the URL:https://drive.google.com/file/d/1L8U01tf4Ss1q4-0yEjj69syFsNVUTWIA/view?usp=drive_link

Project Steps:
1. Load Dataset
2. Data cleaning - Remove redundant and not useful columns
3. Data Splitting - As it is supervised learning, separated Inputs and Targets
4. Handle missing values - For both numerical and categorical data
5. Check and handle data imbalance - Using class weights
6. Data Visualization
7. Data preprocessing - Data encoding and standardization
8. Deep Learning Model Architecture: Layer 1 --> Dense(128),BatchNorm,Relu,Dropout. Layer 2--> Dense(64),BatchNorm,Relu,Dropout. Output Layer-->Dense(1),Sigmoid activation
9. Model Training with Early Stopping with Adam Optimizer and class weights
10. Model Evaluation
