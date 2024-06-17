# **Random Forest Modeling for Customer Satisfaction Prediction**

## **Introduction**

Random forests are widely recognized for their ability to reduce variance, bias, and the risk of overfitting in statistical learning. This project extends our initial decision tree modeling efforts for an airline by focusing on training, tuning, and evaluating a random forest model. The dataset comprises survey responses from 129,880 customers, including data points such as travel class, flight distance, and inflight entertainment.

The primary goal is to predict whether a customer will be satisfied with their flight experience using a random forest model. This project begins with exploratory data analysis (EDA), data cleaning, and necessary manipulations to prepare the dataset for modeling.

## **Project Structure**

- **`data/`**: Contains the dataset used for the analysis.
  - `survey_responses.csv`: The dataset with customer survey responses.
- **`notebooks/`**: Jupyter notebooks documenting the project workflow.
  - `random_forest_modeling.ipynb`: Main notebook for data analysis, cleaning, and random forest modeling.
- **`scripts/`**: Python scripts used for data processing and modeling.
  - `data_preprocessing.py`: Script for cleaning and preprocessing the data.
  - `random_forest_model.py`: Script for training and evaluating the random forest model.
- **`reports/`**: Generated analysis and model evaluation reports.
  - `model_evaluation.pdf`: Detailed evaluation of the random forest model’s performance.
- **`README.md`**: Project overview and instructions (this file).

## **Setup and Usage**

### **Prerequisites**

Ensure you have the following software and libraries installed:

- Python 3.7 or later
- Jupyter Notebook
- Required Python libraries listed in `requirements.txt`

### **Installation**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your_username/random-forest-customer-satisfaction.git
