# Indian Crime Analysis and Visualization Using Machine Learning

## Project Overview
This project analyses and visualizes crime data across India using machine learning techniques. It aims to identify patterns in crime rates, classify districts based on crime intensity, and provide interactive geospatial visualizations for easy interpretation.

## Features
- **Data Preprocessing**: Cleaned and scaled numerical features like Crime Code, Victim Age, and Police Deployed.
- **Dimensionality Reduction**: Applied Kernel PCA to reduce dimensionality and visualize crime patterns effectively.
- **Clustering**: Used KMeans clustering to categorize areas as low, medium, or high crime zones.
- **Classification**: Built a Random Forest classifier to predict crime intensity in districts, evaluated using a confusion matrix.
- **Geospatial Visualization**: Interactive maps created with Folium, displaying city-level crime clusters across India.

## Dataset
- The dataset contains crime reports from multiple Indian cities with columns such as `City`, `Crime Code`, `Crime Description`, `Victim Age`, `Police Deployed`, and more.
- Ensure the dataset is saved as `india_crime_data.csv` in the project directory.

## Installation
Install required Python packages using pip:

```bash
pip install numpy pandas matplotlib scikit-learn folium geopy
