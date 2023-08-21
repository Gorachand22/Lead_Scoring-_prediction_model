## Lead Conversion Prediction Project

This project involves building a logistic regression model to predict the probability of lead conversion for a business. The dataset used for this analysis contains information about various attributes of leads and their interactions with the business's website.

### Problem Statement
The company's lead conversion rate is currently suboptimal, and there is a need to develop a predictive model that can assign lead scores based on the probability of conversion. The ultimate goal is to improve the conversion rate and prioritize leads with higher potential for conversion.

### Dataset
The dataset used for this project includes information about leads, including their source, engagement on the website, occupation, and other relevant attributes. It also includes the binary outcome variable "Converted," indicating whether a lead converted or not.

### Business Objective
The primary objective of this analysis is to build a logistic regression model that can predict the likelihood of a lead converting into a customer. By identifying the key factors that influence conversion probability, the company can focus its efforts on high-potential leads and tailor its marketing strategies accordingly.

## Approach
The analysis begins with exploratory data analysis (EDA) to understand the distribution of variables, identify patterns, and assess the relationship between features and the target variable. Data cleaning and preprocessing are performed, including handling missing values, encoding categorical variables, and scaling numeric features.

Feature selection is carried out using various techniques, including coefficient analysis and recursive feature elimination (RFE), to identify the most influential variables for predicting lead conversion.

The logistic regression model is then built using the selected features, and its performance is evaluated using metrics such as accuracy, precision, recall, and the receiver operating characteristic (ROC) curve.

### Results and Conclusions
The logistic regression model demonstrates strong predictive performance in identifying leads with a higher likelihood of conversion. The top features contributing to lead conversion include `Total Time Spent on Website`, `Lead Source_Welingak website`, `Lead Source_Reference`, `Last Activity_Email Opened`, and `Last Activity_SMS Sent`.

The insights gained from this analysis can guide the company's lead management strategy by focusing on leads with higher predicted conversion probabilities. This targeted approach can lead to increased conversion rates, efficient resource allocation, and improved overall sales performance.

### Repository Structure
<ul>
    <li>data: Contains the dataset used for the analysis.</li>
    <li>notebooks: Jupyter notebooks used for data preprocessing, feature selection, model building, and evaluation.</li>
    <li>README.md: This file providing an overview of the project.</li>
</ul>

### Instructions
To replicate the analysis and model building, follow these steps:
<ul>
    <li>Clone the repository to your local machine.</li>
    <li>Install the required dependencies by running pip install -r requirements.txt.</li>
    <li>Open the Jupyter notebooks in the notebooks directory and execute the cells sequentially.</li>
</ul>

### Contributors<br>
Gorachanda Dash<br>
gorachanddash6121@gmail.com