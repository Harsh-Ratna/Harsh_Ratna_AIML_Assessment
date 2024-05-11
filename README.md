# 📈 Sourcing Cost Prediction Project 

## Overview 📊
In this project, we aim to predict the sourcing costs for different product combinations using regression analysis. By leveraging machine learning techniques, we'll uncover insights into the factors influencing sourcing costs and build models to improve cost estimation accuracy.

## Dataset 📋
The dataset used for this project contains the following columns:
- Product Name
- Manufacturer
- Area Code
- Sourcing Channel
- Product Size
- Product Type
- Month of Sourcing
- Sourcing Cost
  
Except the target variable(Sourcing Cost) all the other features are categorical in nature. Month of Sourcing Column indicates the month in which the product combination is sourced.
The Shape of the original Train Data is (550176, 8).

## Methodology 🔍
1. **Data Exploration:** Explore the dataset to understand variable distributions and identify key insights.
2. **Data Preprocessing:** Cleanse and preprocess the data to prepare it for modeling.
3. **Feature Engineering:** Extract meaningful features and engineer new ones to enhance model performance.
4. **Model Selection:** Experiment with different regression models such as Linear Regression, Random Forest, and Gradient Boosting to find the best fit.
5. **Model Evaluation:** Evaluate model performance using metrics like Mean Absolute Error (MAE) and R-squared to assess accuracy and generalization capability.
6. **Interpretation:** Interpret model coefficients and feature importance to gain actionable insights into cost drivers. 📈

## Files 📂
- `data.csv`: Raw dataset containing product attributes and sourcing costs.
- `preprocessed_data.csv`: Cleaned and preprocessed dataset ready for model training.
- `model.py`: Python script for training and evaluating regression models.
- `predict.py`: Python script for making predictions using the trained model.
- `requirements.txt`: List of Python dependencies required to run the project.

## Usage 🚀
1. **Data Preparation:** Ensure the `data.csv` file is in the project directory.
2. **Install Dependencies:** Install required Python packages using `pip install -r requirements.txt`.
3. **Model Training:** Run `model.py` to train and evaluate regression models.
4. **Prediction:** Use `predict.py` to make predictions for new data.

## Results 📈
- Our trained model achieves an impressive R-squared score of X on the test set, indicating strong predictive performance. 💪
- Feature X emerges as the most influential factor in predicting sourcing costs, followed closely by feature Y and Z.

## Conclusion 🎉
In conclusion, the Sourcing Cost Prediction Project provides valuable insights into optimizing procurement processes and improving cost estimation accuracy. Let's continue innovating and driving positive change together! 🌟

## Acknowledgements 🙏
- Special thanks to all contributors and collaborators who made this project possible. Together, we're shaping the future of procurement! 🌍


