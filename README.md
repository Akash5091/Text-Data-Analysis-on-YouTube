# YouTube Analysis Project

## Overview

This project performs an analysis of YouTube comments to uncover insights related to audience engagement, popular content features, and comment trends. It includes data preprocessing, exploration, visualization, and advanced analysis using Python libraries.

## Dataset

The dataset used in this analysis is `UScomments.csv`, which contains YouTube comments data. The dataset includes the following columns:
- `video_id`: Unique identifier for each video.
- `comment_text`: Text of the user comments.
- `likes`: Number of likes received on the comment.
- `replies`: Number of replies to the comment.

## Key Features

- **Data Loading and Cleaning**: Handled missing and mixed-type data to ensure smooth analysis.
- **Data Exploration**: Gained insights into audience preferences using statistical and visual techniques.
- **Visualization**: Created interactive and static visualizations to highlight trends in comments, likes, and replies.
- **Sentiment Analysis**: Used Natural Language Processing (NLP) techniques to categorize comments as positive, negative, or neutral.

## Libraries Used

The project leverages the following Python libraries:
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib` and `seaborn`: For data visualization.
- `nltk`: For sentiment analysis.

## Steps in the Notebook

1. **Data Loading**  
   The dataset is loaded using `pandas.read_csv`, skipping bad lines to handle potential inconsistencies.

2. **Data Cleaning**  
   Addressed missing values and formatted data types for smooth operations.

3. **Exploratory Data Analysis (EDA)**  
   - Summary statistics to understand distributions of likes and replies.
   - Visualization of comment trends.

4. **Sentiment Analysis**  
   Analyzed the sentiment of comments using NLP techniques.

5. **Key Insights**  
   Summarized findings to support data-driven decision-making for content strategy.
