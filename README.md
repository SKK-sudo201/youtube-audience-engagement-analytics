# YouTube Audience Engagement and Content Performance Analytics

## Project Overview
This project analyzes YouTube trending videos and audience comments to identify content-performance patterns, category trends, viewer sentiment, emoji usage, and the relationship between video reach and audience engagement.

The analysis was completed using Python, Pandas, NLTK, Emoji, and Plotly. The project converts raw video and comment data into visual insights that could support content creators, marketing teams, and media organizations.

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
The analysis uses YouTube trending videos and comment datasets containing fields such as:
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
# 1. Audience Engagement by Category
<img width="1094" height="360" alt="Audience Engagement by Category" src="https://github.com/user-attachments/assets/25e37195-3661-4ec8-ac48-53a341a873f4" />

This visualization compares the distribution of engagement rates across YouTube categories.

# Key observations
- Most YouTube categories have relatively low average engagement, with only a few videos receiving exceptionally high interactions.
- Entertainment, Gaming, Comedy, People & Blogs, and Science & Technology show the highest engagement potential, with several videos performing significantly better than others.
- Movies, Shows, and Trailers have the lowest and most consistent engagement rates, indicating fewer highly engaging videos.
- Overall, a small number of viral videos drive most of the engagement across all categories.

# 2. Category Attention Share and Engagement Efficiency
<img width="1094" height="360" alt="Category attention share with Engagement Efficiency Overlay" src="https://github.com/user-attachments/assets/ecc42bdc-d062-45c8-89a7-6b0b4dfe681a" />

The size of each rectangle represents the category's share of audience attention, while the color represents average engagement efficiency.

# Key observations
- Music attracts the largest share of audience attention, followed by Entertainment, making them the most popular content categories.
- Comedy also shows strong engagement efficiency, indicating that viewers interact well with this type of content.
- Some smaller categories generate high engagement despite having fewer views, showing that popularity and engagement are not always the same.
- This analysis helps identify categories that attract both a large audience and active viewer participation.

# 3. Views versus Engagement Rate
<img width="1094" height="360" alt="Engagement Bubble Map- Views vs Engagement Rate" src="https://github.com/user-attachments/assets/d67615f9-08cc-41d4-83e6-ae960bd32bef" />

The bubble chart examines the relationship between video views and engagement rate. Bubble size represents the selected video-performance measure, while color identifies the content category.

# Key observations
- Videos with higher views do not always have higher engagement.
- Many videos with low to medium views receive stronger audience interaction than highly viewed videos.
- Music dominates in total views but does not always achieve the highest engagement rate.
- This shows that both views and engagement should be considered when evaluating a video's overall performance.

# 4. Audience Emotion through Emoji Usage
<img width="1094" height="360" alt="Most used emojis in YouTube comments" src="https://github.com/user-attachments/assets/892284db-3bda-4800-8e3f-9762492c5e89" />

Emoji frequency was analyzed to identify common emotional reactions expressed in viewer comments.

# Key observations
- The most frequently used emojis are 😂, ❤️, and 😍, indicating that viewers generally express positive emotions.
- Positive emojis appear much more often than negative ones, suggesting an overall positive audience response.
- Emoji analysis provides additional insight into viewer emotions beyond traditional sentiment analysis.
- These findings can help content creators better understand how audiences react to their videos.

# 5. Trending Momentum over Time
<img width="1094" height="360" alt="Trending Momentum over Time by Category" src="https://github.com/user-attachments/assets/324d4686-564f-4886-9bce-b8439589c9b8" />

This visualization tracks category-level trending momentum over time.

# Key observations
- Music consistently receives the highest audience attention throughout the analyzed period.
- Entertainment and Sports also experience regular spikes, often driven by popular events or trending topics.
- Audience interest changes over time, with noticeable increases and decreases across different categories.
- Monitoring these trends can help creators identify the best time to publish content and focus on high-performing categories.

- ## Metric Definitions
- # Engagement Rate
- Engagement rate measures audience interaction relative to video reach.

   Engagement rate = (likes + comment count) / all views

- # Engagement Efficiency
  Engagement efficiency was used to compare interaction performance across categories after accounting for audience attention.

-  Engagement efficiency = ('engagement_rate', 'mean')

-  # Business Recommendations
- Focus on content categories with consistently high engagement, such as Entertainment, Gaming, and Comedy.
- Evaluate both views and engagement together, as popular videos do not always generate the strongest audience interaction.
- Study high-engagement videos to identify successful content patterns and improve future content strategies.

- # Limitations
- The dataset represents a specific time period and may not reflect current YouTube trends.
- Automated sentiment analysis may not accurately capture sarcasm or contextual meaning in comments.
- This analysis identifies patterns and relationships but does not establish cause-and-effect between views and engagement.

- # Future Enhancements
- Integrate live YouTube data using the YouTube Data API.
- Create an interactive dashboard for easier data exploration and reporting.
- Use machine learning to predict which videos are likely to receive high engagement.
