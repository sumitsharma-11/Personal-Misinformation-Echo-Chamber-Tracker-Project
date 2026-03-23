# Personal-Misinformation-Echo-Chamber-Tracker-Project

Personal Misinformation & Echo-Chamber Tracker 🛡️🧠

Project Overview

This Power BI dashboard is designed to provide a critical audit of personal content consumption on platforms like YouTube. By analyzing watch history and enriched metadata, the project calculates how much of a "filter bubble" or "echo chamber" a user is currently in. It tracks sentiment, topic diversity, and potential exposure to polarized content.
The goal is to increase digital mindfulness by visualizing whether our online habits are narrowing our perspectives or exposing us to overwhelmingly negative/misinformative sentiments.

Key Performance Indicators (KPIs)

Echo Chamber Index: A custom gauge metric that measures the concentration of specific topics. High scores indicate a narrow "bubble."
Diversity Score: Evaluates the variety of unique topics and viewpoints consumed over time.
Sentiment Analysis: A breakdown of content into Positive, Neutral, and Negative categories to monitor the emotional tone of your feed.
Topic Coverage: Identification of dominant Topic Names to see what dominates your attention (e.g., Politics, Tech, Gaming, News).

Visualizations

Sentiment Trends (Stacked Area Chart): Tracks the evolution of positive vs. negative content consumption over months and years.
Echo Chamber Gauge: A visual warning system showing the intensity of your current content bubble.
Topic Word Cloud: A dynamic visual showing the most frequent keywords and themes in your digital diet.
Content Volume (Card Visuals): Quick stats on Total Videos watched and percentage of polarized content.
Category Breakdown (Donut Chart): A proportional view of your digital interests.

Technical Details

Data Source: YouTube History (enriched via Python/NLP scripts for sentiment and topic extraction).
Data Modeling: A star schema approach centered around the youtube_enriched_data fact table.
DAX Measures:
             Echo_Chamber_Index: Complex calculation based on topic frequency and variance.
             Diversity_Score: Measures unique topic count against total volume.
             Positive/Negative Content %: Percentage of total watch time spent on specific sentiment categories.
Theme: Optimized with the "Bloom" Power BI theme for high readability and modern aesthetic.
