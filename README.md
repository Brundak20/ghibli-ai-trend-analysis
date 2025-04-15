# Ghibli AI Art Trend Analysis

## Overview
This project analyzes the viral trend of Ghibli AI Art, a popular topic that took over social media platforms like Reddit and sparked massive search interest on Google. The art style, inspired by Studio Ghibli, was generated using AI models and shared extensively across various platforms, leading to significant public attention.

In this project, I delve into how this trend gained traction by performing detailed sentiment analysis on Reddit posts, tracking Google search trends, and analyzing regional and global interest. The analysis reveals intriguing insights about the virality of Ghibli AI art and the discussions surrounding it.

## Project Structure

/ghibli-ai-trend-analysis  # Root directory of your project
│
├── /data  # Contains the raw data files used for analysis
│   ├── World_Countries_Generalized/  # Folder with the shapefiles and associated files
│   ├── ghibli_interest_by_region.csv
│   ├── ghibli_interest_by_time.csv
│
├── /notebooks  # Jupyter Notebooks containing analysis code
│   ├── ghibli_trend_analysis.ipynb  # Main notebook with Ghibli trend analysis
│
├── /visualizations  # Generated visualizations (charts, maps, etc.)
│   ├── sentiment_analysis_Reddit.png
│   ├── ghibli_interest_map.png
│   ├── ghibli_google_trend_annotated.png
│   └── daily_reddit_posts.png
│   └── ghibli_interest_by_country.png
│   └── ghibli_top_comments_plot.png
│   └── top10_ghibli_interest_by_country_htmp.png
│
├── .gitignore  # Git ignore file to exclude unnecessary files
├── README.md  # Project overview and instructions
└── requirements.txt  # List of required dependencies


### Data Used:

- **Reddit Data**: Extracted using the PRAW API, analyzing sentiment and user engagement with posts related to Ghibli AI art.
- **Google Search Trends**: A CSV file containing search interest data over time, showing how interest in Ghibli AI art spiked dramatically in March 2025.
- **Geospatial Data**: 
  - **Shapefile**: World_Countries_Generalized - A shapefile used for mapping global interest in Ghibli AI art. This shapefile includes geometries for countries around the world.

### Files:

- **ghibli_trend_analysis.ipynb**: The Jupyter notebook containing the full analysis and visualizations for Ghibli AI trends.
- **Sentiment Analysis**: Analysis of the sentiment on Reddit posts using various sentiment analysis techniques.
- **Global Interest Maps**: Maps displaying the geographical spread and intensity of interest in Ghibli AI art.
- **Charts and Plots**: Various visualizations to display the trends and sentiment distributions.


## Requirements
- Python 3.x
- Jupyter Notebook
- Pandas
- Plotly
- Seaborn
- PRAW (for Reddit data extraction)
- VADER SentimentIntensityAnalyzer
- Selenium (for screenshot generation)
- Matplotlib
- Folium
- Geopandas
- Webdriver-Manager
- PIL

Run the Jupyter Notebook: Open the notebook ghibli_trend_analysis.ipynb in Jupyter or Jupyter Lab to execute the analysis.

## Key Findings
- Viral Surge: Google search interest peaked dramatically on March 30, 2025, marking the viral moment of Ghibli AI art.

- Global Interest: Countries like India, Sri Lanka, and the UAE showed the highest interest in Ghibli AI, especially in South Asia and the Middle East.

- Sentiment on Reddit: Analysis of Reddit posts revealed a mixture of neutral (44%), negative (36.9%), and positive (19%) sentiments surrounding the trend.

## Conclusion
This analysis provides valuable insights into the Ghibli AI Art trend’s rise and its global spread. By tracking the trend's Google search activity and analyzing Reddit engagement, we gain a deeper understanding of the emotional and social engagement surrounding AI art. The project showcases the power of data science in unraveling the dynamics of online trends.

## Usage
You can explore and modify the notebook to further analyze trends or use the data for creating new insights. The included shapefile can be used to visualize global patterns and regional differences in interest.

## Installation

# Clone the repository:
git clone https://github.com/your_username/ghibli-ai-trend-analysis.git


# Install dependencies by running:
   pip install -r requirements.txt

