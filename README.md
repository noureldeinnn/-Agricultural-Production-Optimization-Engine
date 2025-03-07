# Agriculture Production Optimization Engine

## Project Overview
This project aims to predict the best crop to grow based on various agricultural parameters. The dataset includes features such as N (Nitrogen), P (Phosphorus), K (Potassium), Temperature, Humidity, pH, and Rainfall.  
The target variable is a label representing 21 different crop classes.

## Dataset and Preprocessing
An experimental data analysis was conducted, and all values were retained without removing outliers. Further investigation revealed that the identified outliers were meaningful, especially for crops requiring high water and specific NPK levels.  
Therefore, no outliers were removed, and all values were kept intact.

## Algorithms Used
Four algorithms were employed to analyze the data:

- **KNN Clustering**: Achieved a high accuracy of 0.98.
- **KMeans Clustering**: Had a lower performance with an inertia of 2331.
- **DBSCAN**: Demonstrated the worst performance among the algorithms.
- **Logistic Regression**: Performed well with an accuracy of 0.98.

## Conclusion
The Agriculture Production Optimization Engine effectively utilizes machine learning techniques to recommend suitable crops based on input parameters, maintaining data integrity by keeping all values.
