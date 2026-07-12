# YouTube Audience Engagement and Content Performance Analytics

## Project Overview
This project analyzes YouTube trending videos and audience comments to identify
content-performance patterns, category trends, viewer sentiment, emoji usage,
and the relationship between video reach and audience engagement.

The analysis was completed using Python, Pandas, NLTK, Emoji, and Plotly. The
project converts raw video and comment data into visual insights that could
support content creators, marketing teams, and media organizations.

## Business Problem
Businesses and content creators need to understand which YouTube content categories generate the highest audience engagement so they can create more effective content and improve viewer interaction.

# This project addresses the following questions:
1. Which YouTube categories attract the greatest audience attention?
2. Which categories generate stronger engagement relative to their reach?
3. Do viral videos maintain high engagement rates?
4. What emotions are commonly expressed in YouTube comments?
5. How does category momentum change over time?

## Tools and Technologies
- Python
- Pandas
- NumPy
- NLTK VADER
- Emoji
- Plotly
- Matplotlib
- Jupyter Notebook
- CSV and JSON

## Dataset
The analysis uses YouTube trending videos and comment datasets containing fields
such as:
- Video ID
- Video title
- Category ID
- Views
- Likes
- Dislikes
- Comment count
- Trending date
- Comment text

## Analysis Workflow
1. Imported video, comment, and category-mapping data
2. Examined structure, data types, missing values, and duplicate records
3. Cleaned and standardized video and comment data
4. Mapped category IDs to readable category names
5. Engineered audience-engagement and efficiency metrics
6. Performed sentiment analysis on viewer comments
7. Extracted and counted emojis from comments
8. Compared engagement across content categories
9. Examined views versus engagement behavior
10. Tracked category momentum over time
11. Developed interactive visualizations and business recommendations

## Key Performance Indicators
- Total views
- Likes
- Dislikes
- Comment count
- Engagement rate
- Engagement efficiency
- Category attention share
- Sentiment distribution
- Emoji frequency
- Trending momentum

## Dashboard and Visual Analysis
<img width="1094" height="360" alt="Audience Engagement by Category" src="https://github.com/user-attachments/assets/25e37195-3661-4ec8-ac48-53a341a873f4" />
<img width="1094" height="360" alt="Trending Momentum over Time by Category" src="https://github.com/user-attachments/assets/324d4686-564f-4886-9bce-b8439589c9b8" />
<img width="1094" height="360" alt="Most used emojis in YouTube comments" src="https://github.com/user-attachments/assets/892284db-3bda-4800-8e3f-9762492c5e89" />
<img width="1094" height="360" alt="Engagement Bubble Map- Views vs Engagement Rate" src="https://github.com/user-attachments/assets/d67615f9-08cc-41d4-83e6-ae960bd32bef" />
<img width="1094" height="360" alt="Category attention share with Engagement Efficiency Overlay" src="https://github.com/user-attachments/assets/ecc42bdc-d062-45c8-89a7-6b0b4dfe681a" />
