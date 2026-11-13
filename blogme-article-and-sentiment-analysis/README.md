# BlogMe Article Analysis & Sentiment Analysis

Python data cleaning, VADER sentiment analysis, and an interactive Tableau dashboard for exploring news article engagement, headline sentiment and publisher performance.

📊 [View the dashboard on Tableau Public](https://public.tableau.com/app/profile/teodora.maksimovic/viz/BlogMeArticleAnalysisSentimentAnalysis_17945762631820/BlogMeNewsDashboard)

![BlogMe News Dashboard](<BlogMe News Dashboard.png>)

> The screenshot is static. Open the Tableau Public link to use the interactive filters and explore the visualizations.

## What I did

- **Python (pandas):** loaded and cleaned news article data, processed article titles, and created keyword-based flags to identify articles mentioning specific terms such as *murder*. Exported the cleaned dataset for visualization ([notebook](blog_me.ipynb)).
- **Sentiment Analysis (VADER):** used `SentimentIntensityAnalyzer` to analyze article headlines and calculate positive, negative, and neutral sentiment scores.
- **Tableau:** built an interactive dashboard to analyze article engagement over time, compare positive and negative headlines, and evaluate publisher performance. Connected article and source data and created calculated fields for total engagement and sentiment classification.

## Key Insights

- Article engagement varies considerably across news headlines, with certain articles generating significantly more interactions than others.
- CNN, The New York Times, and BBC News are among the leading publishers by total engagement in the analyzed dataset.
- Headlines classified as positive and negative show different engagement patterns, allowing comparison of audience interactions across sentiment categories.
- Three of the four most-engaged articles containing the keyword *murder* mention Amber Guyger, highlighting the significant audience engagement surrounding this case.

## Dashboard Features

- Interactive filters (publication date and news source) for exploring article engagement.
- Line charts showing engagement trends over time, including comments, reactions, and shares.
- Bar charts displaying top positive and negative sentiment headlines ranked by total engagement.
- Keyword-based analysis of articles mentioning *murder* int the title.
- Publisher comparison chart showing total engagement by news source and headquarters location.

## Tools

Python (pandas, NumPy, VADER Sentiment) · Tableau Public

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
