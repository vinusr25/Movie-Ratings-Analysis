# Movie Ratings Analysis

## Project Goal
Analyze movie ratings and trends by genre, year, and director using Python, Pandas, and Seaborn.  
This project demonstrates data cleaning, exploratory analysis, visualizations, and insights from a real-world dataset.

## Dataset
- Source: [Kaggle Movie Dataset](https://www.kaggle.com/datasets/PromptCloudHQ/imdb-data)
- Contains 1000 movies with features such as Title, Genre, Director, Year, Rating, Votes, Revenue, and Metascore.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab 

## Steps Performed

### 1. Data Cleaning
- Removed missing ratings
- Converted Year to integer
- Extracted main genre from multi-genre entries

### 2. Exploratory Data Analysis
- Ratings distribution (histogram)
- Average rating by genre (bar chart)
- Average rating by year (line plot)
- Top 10 directors by average rating (bar chart)
- Top 10 highest-rated movies (table)
- Correlation heatmap of numeric features

### 3. Visualizations
- Histograms, bar charts, line plots, and heatmaps
- Example plots (replace placeholders with your actual images):
  ![Ratings Distribution](images/ratings_distribution.png)
  ![Average Rating by Genre](images/average_rating_genre.png)
  ![Correlation Heatmap](images/correlation_heatmap.png)

### 4. Insights
- Genres like Action and Adventure tend to have higher average ratings
- Movie ratings show trends over years
- Certain directors consistently produce high-rated movies
- Correlations highlight relationships between Ratings, Votes, Revenue, and Runtime

## Top 10 Movies (Sample)
| Title | Year | Genre | Director | Rating |
|-------|------|-------|----------|--------|
| Guardians of the Galaxy | 2014 | Action | James Gunn | 8.1 |
| Split | 2016 | Horror | M. Night Shyamalan | 7.3 |
| Prometheus | 2012 | Adventure | Ridley Scott | 7.0 |
| Sing | 2016 | Animation | Christophe Lourdelet | 7.2 |
| Suicide Squad | 2016 | Action | David Ayer | 6.2 |
| … | … | … | … | … |

## How to Run
1. Upload `movies.csv` to your environment (Google Colab or Jupyter Notebook)
2
