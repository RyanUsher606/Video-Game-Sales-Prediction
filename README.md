# Video-Game-Sales-Prediction

This project involves analyzing and predicting video game sales using a dataset obtained from Kaggle. The dataset includes various features like platform, genre, year of release, and global sales.

Key Steps:

Data Cleaning:

Handled missing values by dropping rows with null values in the "Publisher" column and filling missing "Year" values with the median year.

Converted the "Year" column to integer data type.

Data Visualization:

Created visualizations to explore sales trends over the years, the impact of different genres, and platform-specific sales using Seaborn and Matplotlib.

Feature Encoding:

Transformed categorical columns (Name, Platform, Genre, Publisher) into numerical values using LabelEncoder for machine learning model compatibility.

Data Preparation:

Dropped unnecessary columns like 'Global_Sales', 'JP_Sales', and 'Other_Sales' to focus on predicting 'Global_Sales'.

Split the data into training and testing sets.

Model Development:

Implemented a Linear Regression model to predict global sales based on the available features.

Evaluated the model by plotting predicted values against actual values.

Tools and Libraries:

Python

Pandas for data manipulation

Seaborn and Matplotlib for data visualization

Scikit-learn for model training and evaluation

Acknowledgments:

Dataset: This project uses the video game sales dataset provided by Kaggle, which serves as the foundation for all analysis and predictions.
