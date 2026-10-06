# Article Recommendation System

A data science and machine learning project to develop a personalised article recommendation system using reader interaction history and article metadata.

## Business Problem

How can a media company use reader behaviour and article information to provide more relevant content recommendations, improve engagement, and support potential subscription conversion?

## Objective

Develop an article recommendation approach that recommends relevant articles based on readers' historical interactions and article characteristics.

## Dataset

The project uses three datasets:

- User Demographics
- User Article History
- Article List

Dataset size:

- 305 readers
- 14,475 interaction records
- 8,043 articles

## Approach

The project follows these steps:

1. Data understanding and quality assessment
2. Data cleaning and preprocessing
3. Exploratory data analysis
4. Feature engineering
5. Recommendation modelling
6. Model evaluation
7. Business recommendations

Two recommendation approaches were considered:

- **Popularity-based recommendation** – baseline
- **Content-based recommendation** – proposed approach

## Data Preparation

Key preprocessing steps included:

- Handling missing article IDs
- Removing unmatched article records
- Handling missing article sentiment
- Standardising demographic categories
- Grouping rare article categories
- Removing repeated reader-article impressions
- Standardising datetime formats

## Evaluation

The recommendation approaches were evaluated using:

- ROC-AUC
- Precision@3
- Lift@20%

The content-based approach showed better performance than the popularity-based baseline.

## Business Recommendation

A personalised recommendation module could be integrated into:

- Homepage
- Article pages
- "Recommended for You" sections

The main KPI would be **article views / CTR**, with potential improvements in reader retention and subscription conversion.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Project Structure

```text
article-recommendation-system/
│
├── README.md
└── article_recommendation_system.ipynb
