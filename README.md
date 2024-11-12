# Brazilian E-Commerce Analysis Project

This project provides a comprehensive analysis of a Brazilian e-commerce dataset. It includes exploratory data analysis (EDA) to uncover customer purchasing trends, demand patterns, and product-related insights. Additionally, an NLP-based sentiment analysis is performed on product reviews, coupled with machine learning modeling for predicting key outcomes.


## Dataset Information

- **Source**: Brazilian e-commerce dataset taken from [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).
- **Contents**: Customer, product, and transaction data, including features like purchase time, product category, review scores, and text reviews.


## Project Goals

1. Analyze customer purchasing behaviors and identify demand patterns.
2. Use NLP to evaluate customer sentiments through review analysis.
3. Apply machine learning to predict aspects of customer behavior or product trends.


## Methodology
- **Data Cleaning**: Preprocessing to handle missing values, correct data types, and remove irrelevant information.
- **Exploratory Data Analysis**: Uncover patterns in customer behavior, demand peaks, and product popularity.
- **NLP Analysis**: Tokenization, sentiment analysis, and categorization of review text.
- **Machine Learning Models**: Model selection and evaluation for predictive analysis based on customer and transaction data.


## Exploratory Data Analysis

### Key insights into:

- Customer demographics and behavior.
- Product demand patterns and sales peaks.
- Order metrics, including delivery times and customer satisfaction.

 ## NLP and Sentiment Analysis

The sentiment analysis leverages Natural Language Processing (NLP) techniques to evaluate product reviews, helping identify trends in customer satisfaction. Steps include:

- Tokenization of review text.
- Sentiment score calculation.
- Analysis of review sentiment across product categories.

## Machine Learning Modeling

Predictive modeling is applied to understand and forecast key factors within the e-commerce data, enhancing our understanding of customer actions and product preferences.

### Key Findings

- Identified customer segments with varying purchasing behaviors.
Determined the impact of certain product attributes on customer satisfaction.
Developed a review-based sentiment profile for key product categories.

## Dataset Download Instructions
To run this project, you’ll need to download the credit card fraud detection dataset:

- Download the dataset from [Kaggle’s Brazilian E-Commerce Dataset page](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).
- Save the downloaded `csv` files in the same directory as the Jupyter Notebook (`brazilian-e-commerce-eda-nlp-ml.ipynb`).
 
## How to Use This Project

- Clone the repository.
```bash
  git clone https://github.com/AnnaAnastasy/Brazil-E-Commerce.git
```
- Ensure Python 3.7+.
- Install required libraries listed in `requirements.txt`.
```bash
  pip install -r requirements.txt
```
- Run the Notebook: Open and execute `brazilian-e-commerce-eda-nlp-ml.ipynb` in a Jupyter Notebook environment.

## Conclusions
This project provides actionable insights into Brazilian e-commerce, revealing key trends in customer purchasing behavior, high-demand product categories, and peak sales periods. Sentiment analysis of customer reviews further highlighted areas for customer satisfaction improvements, such as delivery and product quality. Together, these insights can help e-commerce businesses optimize inventory, refine marketing strategies, and enhance the overall customer experience.
