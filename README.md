# Predicting Cross-Country Content Spread

## Project Overview

This project investigates whether linguistic similarity between nations (shared languages and linguistic proximity) influences the international spread of digital content. By combining trending data from the YouTube Data API with linguistic indices from the DICL Database, the study builds a predictive model to determine if a video popular in one country will "cross over" and trend in another.

## Tech Stack

- **Programming Language:** Python 3  
- **Environment:** Google Colab / Jupyter Notebook  
- **Data Collection:** YouTube Data API v3, Custom Python Scraper  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Preprocessing Tools:** OneHotEncoder, StandardScaler, Log Transformation  
- **Machine Learning Algorithms:**  
  - Random Forest Classifier  
  - Histogram-Based Gradient Boosting Classifier  
- **Optimization Techniques:**  
  - Hyperparameter Tuning  
  - Class Weight Balancing  
  - Threshold Tuning  

## Data Sources

- **YouTube Trending Videos:** Metadata and engagement metrics for the top videos per country  
- **DICL v2 Database:** Linguistic similarity indices between countries (official languages, native languages, proximity measures)  

## File Structure

```text
youtube-cross-country-analysis.ipynb        # Main analysis notebook
DICL_v2.csv                                 # Linguistic similarity dataset
youtube_most_popular.csv                    # YouTube trending videos data
cleaned_merged_dataset.csv                  # Preprocessed combined dataset
README.md                                   # Project overview
