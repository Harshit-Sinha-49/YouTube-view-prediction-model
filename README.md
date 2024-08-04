</p>
<h1 align = 'center'>YouTube View Count Prediction and Viewers Analsysis Model</h1>
<br>
</p>

## Description:
This model focuses on the predictive analysis of YouTube view counts, employing the CatBoost algorithm to model and forecast viewership trends. Leveraging the [YouTube API](https://developers.google.com/youtube/v3), data was collected from a specific channel, encompassing video metadata and comment section sentiment analysis to provide a comprehensive understanding of audience engagement dynamics. 

## Techn Stack
<div style="display: flex; flex-direction: row;">
<img src="Images/python.png" width="75" height="75" style="margin-right: 25px;">
<img src="Images/jupyter.png" width="75" height="75" style="margin-right: 25px;">
<img src="Images/pandas-logo.png" width="75" height="75" style="margin-right: 25px;">
<img src="Images/seaborn.svg" width="75" height="75" style="margin-right: 25px;">
</div>
<br>

`Language` : Python <br>
`Library` : Pandas, Matplotlib, Seaborn, NLTK <br>
`Platform` : Juypter Notebook <br>

## Output
View Count Analysis Output:
<div style="display: flex; flex-direction: row;">
 <h3>Views Plot</h3>
<img src="Images/Output/views plot.jpg" width="400" style="margin-right: 25px;">
 <h3>Scatter Plot</h3>
<img src="Images/Output/scatter plot.jpg" width="400" style="margin-right: 25px;">
 <h3>Views Histogram</h3>
<img src="Images/Output/views histogram.jpg" width="400" style="margin-right: 25px;">
<h3>Views Log Histogram</h3>
<img src="Images/Output/views log histogram.jpg" width="400" style="margin-right: 25px;">
<h3>Seasonal Decomposition</h3>
<img src="Images/Output/seasonal decomposition.jpg" width="400" style="margin-right: 25px;">
<h3>Seasonal Pattern</h3>
<img src="Images/Output/seasonal pattern.jpg" width="400" style="margin-right: 25px;">
 <h3>Data Distribution Plot</h3>
<img src="Images/Output/data_distribution plot.jpg" width="400" style="margin-right: 25px;">
 <h3>Heatmap</h3>
<img src="Images/Output/heatmap.jpg" width="400" style="margin-right: 25px;">
  <h3>Catboost (without addition feature)</h3>
<img src="Images/Output/catboost without addition feature.jpg" width="400" style="margin-right: 25px;">
</div>

Viewer Analysis Output:
<div style="display: flex; flex-direction: row;">
 <h3>Boxplot</h3>
<img src="Images/Output/boxplot sentiment.jpg" width="400" style="margin-right: 25px;">
 <h3>Sentiment Distribution</h3>
<img src="Images/Output/sentiment distribution.jpg" width="400" style="margin-right: 25px;">
 <h3>Wordcloud</h3>
<img src="Images/Output/wordcloud.jpg" width="400" style="margin-right: 25px;">
</div>
<br>
## Data collection
Data collection was facilitated through the YouTube API, enabling the extraction of video metadata such as title, description, and tags, along with engagement metrics including likes, dislikes, and comments. Additionally, sentiment analysis was performed on the comment section to gauge audience sentiment and its impact on viewership. 

 ## CatBoost algorithm
The CatBoost algorithm, known for its robustness in handling categorical variables and its ability to mitigate overfitting, was chosen for its suitability in predicting view counts amidst the complex landscape of YouTube content. Through feature engineering and model optimization, our analysis aimed to uncover the key factors influencing video popularity and viewership dynamics. 

## Result
The results of our analysis highlight the significance of various factors such as video length, title sentiment, and viewer interaction in influencing view counts. Furthermore, the CatBoost model demonstrated strong predictive performance, accurately capturing the nuances of audience behavior and content preferences.
