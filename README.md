## Overview
This project aims to analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands. The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/danishmubashar/twitter-sentiment-generator-model), contains tweets labeled with sentiments such as Positive, Negative, Neutral, and Irrelevant. We used Python in a Jupyter notebook for data cleaning, preprocessing, analysis, and visualization.

## Dataset
The dataset consists of tweets labeled with sentiments and is divided into training and validation sets:
- **Training Dataset**: `twitter_training.csv`
- **Validation Dataset**: `twitter_validation.csv`

Each row in the datasets includes an index, entity, sentiment, and text of the tweet.

## Cleaning Process
To ensure data integrity and accuracy, the dataset underwent a cleaning process:
1. **Text Preprocessing**: Converted text to lowercase, removed URLs, mentions, hashtags, non-alphabetic characters, and stopwords.
2. **Handling Missing Values**: Filled missing values in the `cleaned_text` column. 

## Visualization
Various visualizations were created before delving into the detailed examination. A confusion matrix was generated to display the model's performance on the validation dataset, providing a clear view of how well the model predicts each sentiment category. Word clouds highlight prominent words in tweets, offering insights into common themes and topics discussed. Pie charts and bar plots were used to show sentiment distribution, providing an intuitive representation of how sentiments are distributed across different entities. Additionally, a heat map was used to illustrate the correlation between predicted and actual sentiment categories, further enhancing the understanding of model performance and sentiment trends.

## Analysis
The analysis, based on various visualizations, reveals significant variability in sentiment distribution across different entities. Negative sentiment shows the highest variation, indicating differing levels of dissatisfaction or criticism, with entities like "MaddenNFL" and "NBA2K" exhibiting notably high negative sentiment. Positive and neutral sentiments are more evenly distributed but still show significant differences, with entities such as "AssassinsCreed" and "Amazon" showing higher counts of positive and neutral tweets, respectively. Correlation analysis highlights an inverse relationship between negative and positive sentiments across entities.

## How to Use
1. **Accessing the Dataset**: The datasets `twitter_training.csv` and `twitter_validation.csv` can be accessed in the repository.
2. **Data Cleaning, Preprocessing, Visualization, and Analysis**: Refer to the Jupyter notebook file `TASK04.ipynb` provided in the repository for the complete workflow.
