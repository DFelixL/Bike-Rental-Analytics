This project is from my GDSC Data Science/Machine Learning Track Project. This project focuses on analyzing bike rental data to gain insights and create predictive model.

Steps Involved:

1. Data Understanding:
    Firstly, the raw data is examined to identify key attributes, such as rented bike count, hour, humidity, temperature, solar radiation, etc. The structure, types of data, and potential relationships between attributes is also assessed to understand the scope of analysis.

2. Data Cleaning:
    Incomplete records are identified for missing or null values and then removed from the dataset to ensure data consistency. This process involves scanning the dataset for any gaps or missing entries, which may disrupt the accuracy and reliability of the analysis.

3. Data Preprocessing:
    Irrelevant columns are removed from the dataset to ensure a strong correlation between attributes. Additionally, the date is being formatted in a specific way to facilitate easier analysis. The functioning day is also converted from ca ategorical to a numerical format. The season is derived from the month.

4. Data Analysis & Visualization:
    Statistical methods and visualization tools is used to analyze patterns and trends over time. The visualization, such as heatmap, histogram, and box plot, is displayed to highlight key insights.

5. Model Selection, Training, and Evaluation
    Three models are used: Linear Regression, Random Forest, and Gradient Boosting, to predict bike rental probability. The evaluation metrics used are SMAPE and MAE.

Insight gathered :
- The higher the density, the fewer bikes are rented.
- There is no clear pattern in the hourly rental distribution; however, rentals between 0-6 hours are the lowest.
- The SMAPE and MAE scores of the model are still high, indicating that the model is not adequate. Further inspection of the data processing is needed to improve the model.
