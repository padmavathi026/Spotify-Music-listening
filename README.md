# Spotify-Music-listening
<h1>🎧 Spotify Music Listening Behavior Analysis</h1>

<h2>Description</h2>
This project analyzes global Spotify chart data from 2014 to 2022 to uncover insights into music listening behavior over time. Using R and statistical/machine learning techniques, the study explores temporal trends, behavioral clusters, and changes influenced by major events like the COVID-19 pandemic.

<h3>📂 Project Structure</h3>
- <b>Spotify_ProjectReport_code_final.Rmd: Complete R Markdown file containing all data processing, analysis, and visualizations.

- <b>Spotify Music Listening Behaviour.pdf: Final project report with analysis summaries and insights.

- <b>data/: https://www.kaggle.com/datasets/jfreyberg/spotify-chart-data </b>

<h4>🔍 Objective</h4>

- <b>To mine large-scale Spotify chart data and uncover:

- <b>Temporal trends in streaming volume

- <b>Geographic differences in music popularity

- <b>Behavioral patterns using clustering

- <b>Structural changes due to the COVID-19 pandemic

- <b>Survival patterns of songs on the charts </b>


<h5>📈 Techniques Used </h5>

- <b>Exploratory Data Analysis (EDA)

- <b>Principal Component Analysis (PCA)

- <b>Hierarchical Clustering

- <b>ARIMA Time Series Forecasting

- <b>Change Point Detection (CUSUM, e.divisive)

- <b>Survival Analysis (Kaplan-Meier Estimation) </b>

<h6>📌 Key Results</h6>

- <b>Top countries: US, Switzerland, and Poland lead in chart entries.

- <b>Streaming trends showed seasonal dips and COVID-related changes.

- <b>PCA revealed strong inverse correlation between streams and chart position.

- <b>Clustering distinguished low, mid, and high-streaming songs.

- <b>ARIMA forecasted post-2023 recovery in streams.

- <b>Change points detected in early 2020 and late 2021 aligned with pandemic phases.

- <b>Survival analysis showed Top 10 songs lasted significantly longer. </b>

<h7> 📊 Libraries Used </h7>
- <b>tidyverse, ggplot2

- <b>survival, survminer

- <b>changepoint, ecp

- <b>forecast, tseries </b>
<h8>🚀 How to Run </h8>
1. Install required R packages:
   
   install.packages(c("tidyverse", "ggplot2", "survival", "survminer", "changepoint", "ecp", "forecast", "tseries"))
  
3. Open and run the Spotify_ProjectReport_code_final.Rmd in RStudio.

4. Output includes all plots and results within the RMarkdown output.


