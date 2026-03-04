# Fashion Product Recommendation System

This project builds a fashion product recommendation system using machine learning techniques.

The system recommends similar fashion products based on product attributes such as category, color, and product name.

## Technologies Used

Python  
Pandas  
NumPy  
Scikit-learn  
Jupyter Notebook  

## Machine Learning Techniques

TF-IDF Vectorization  
Nearest Neighbors Algorithm  
Cosine Similarity  

## Features

Content-based product recommendation  
Interactive interface using Jupyter widgets  
Recommends similar fashion products based on attributes  

## Dataset

The project uses a fashion product dataset containing product attributes such as:

- product id
- master category
- sub category
- article type
- base colour
- product display name

## How the System Works

1. Dataset is loaded and cleaned.
2. Important product features are combined into a single text feature.
3. TF-IDF vectorization converts text into numerical features.
4. Nearest Neighbors algorithm finds similar products.
5. Users can select a product and receive recommended items.

## How to Run the Project

1. Install required libraries

pip install -r requirements.txt

2. Open the notebook

fashion_product_recommendation_system.ipynb

3. Run all cells to generate recommendations.

## Author

Shruti Jaswal  
MCA – Artificial Intelligence & Machine Learning