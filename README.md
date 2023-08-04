# Credit Card Fraud Detection

The goal of this project is to build a machine learning model that can detect fraudulent credit card transactions from a given dataset.

## Dataset
The dataset used for this project is a CSV file containing credit card transaction data. It includes various features such as time of the transaction, transaction amount, and anonymized features V1 to V28. The target variable is the 'Class' column, where 1 represents a fraudulent transaction and 0 represents a valid transaction.

## Dependancies
The following Python libraries are required to run the code:
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
  
You can install these libraries using pip:
```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Installation
1. Clone the repository to your local machine:
```
git clone https://github.com/melita-celia/credit-card-fraud-detection.git
cd your_folder
```
2. Download the [Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and place it in the project folder:

3. Run the python file:
```
python filename.py
```

## Usage
1. The notebook contains the following sections:
    * Data Loading: Load the dataset into a Pandas DataFrame and perform basic exploratory data analysis.
    * Data Preprocessing: Check for missing values and perform any necessary data preprocessing steps.
    * Data Visualization: Visualize the data to gain insights into the features and target distribution.
    * Model Training: Split the data into training and testing sets, and train a Random Forest Classifier.
    * Model Evaluation: Evaluate the model's performance using various metrics and visualize the confusion matrix.
  
2. Mmodify your code and experiment with different machine learning models or data preprocessing techniques to improve the results.

## Results
The trained Random Forest Classifier achieved an accuracy of approximately 99.96% in detecting credit card fraud. However, it is essential to consider other metrics such as precision, recall, and F1-score, especially in imbalanced datasets.

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/melita-celia/credit-card-fraud-detection/blob/main/LICENSE) file for details.
