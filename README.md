# Netflix Case Study (EDA): Unveiling Data-Driven Strategies for Streaming

## Project Details

In this project, we embark on an exciting journey to explore the intriguing patterns, trends, and insights hidden within Netflix’s content landscape. Leveraging the power of Python and its data analysis libraries, we dive into the vast collection of Netflix’s offerings to uncover valuable information that sheds light on content additions, duration distributions, genre correlations, and even the most commonly used words in titles and descriptions.

### Netflix’s Global Reach

Netflix has experienced remarkable growth and expanded its presence to become a dominant force in the streaming industry. Here are some noteworthy statistics that showcase its global impact:

- **User Base:** By the beginning of the second quarter of 2022, Netflix had amassed approximately 222 million international subscribers, spanning over 190 countries (excluding China, Crimea, North Korea, Russia, and Syria). These impressive figures underline the platform’s widespread acceptance and popularity among viewers worldwide.

- **International Expansion:** With its availability in over 190 countries, Netflix has successfully established a global presence. The company has made significant efforts to localize its content by offering subtitles and dubbing in various languages, ensuring accessibility to a diverse audience.
  
## Table of Contents

1. [Introduction](#introduction)
2. [Data Preparation](#data-preparation)
3. [Exploratory Data Analysis](#exploratory-data-analysis)
4. [Conclusion](#conclusion)
   
## Introduction

As one of the leading streaming platforms globally, Netflix has revolutionized how we consume entertainment. With its vast library of movies and TV shows, it offers an abundance of choices for viewers around the world.

## Data Preparation

The data used in this case study is sourced from Kaggle, a popular platform for data science and machine learning enthusiasts. The dataset, titled [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows), is publicly available on Kaggle and provides valuable information about the movies and TV shows on the Netflix streaming platform.

### Dataset Overview

| Column Name    | Description                                         |
|-----------------|----------------------------------------------------|
| show_id         | Unique ID for every Movie / TV Show                |
| type            | Identifier – A Movie or TV Show                    |
| title           | Title of the Movie / TV Show                       |
| director        | Director of the Movie                              |
| cast            | Actors involved in the Movie / Show                |
| country         | Country where the Movie / Show was produced        |
| date_added      | Date it was added on Netflix                       |
| release_year    | Actual Release Year of the Movie / Show            |
| rating          | TV Rating of the Movie / Show                      |
| duration        | Total Duration – in minutes or number of seasons   |
| listed_in       | Genre in which the content is Listed               |
| description     | A short description of the content                 |

## Exploratory Data Analysis

### Distribution of Content Types

To determine the distribution of content in the Netflix library, we calculated the percentage distribution of content types (movies and TV shows). The pie chart visualization reveals that approximately 70% of the content on Netflix consists of films, while the remaining 30% are TV shows.

### Top 10 Countries Where Netflix is Popular

The bar chart visualization shows that the United States is the top country where Netflix is popular, indicating a significant user base in this region.

### Top 10 Actors by Movie/TV Show Count

Identifying the top 10 actors with the highest number of appearances in movies and TV shows, the bar chart displays that Anupam Kher has the highest number of appearances in Netflix content.

### Top 10 Directors by Movie/TV Show Count

The bar chart showcases the top 10 directors with the most movies or TV shows in the Netflix library, with Rajiv Chilaka leading in the number of content directed.

### Top 10 Categories by Movie/TV Show Count

The bar chart displays the top 10 categories of movies and TV shows based on their count, with "International Movies" being the most dominant category, followed by "Dramas."

### Movies & TV Shows Added Over Time

The line chart illustrates the number of movies and TV shows added to Netflix over time. Notably, Netflix experienced substantial growth starting from 2015, adding more movies than TV shows over the years. The drop in content addition in 2020 could be attributed to the pandemic situation.

### Content Added by Month

Analyzing the month-wise distribution of content additions, the bar chart reveals that July and December are the months when Netflix adds the most content to its library. This information can be valuable for viewers anticipating new releases during these months.

### Distribution of Ratings

The bar chart visualizes the distribution of ratings on Netflix, providing insights into the most common rating categories and their relative frequency.

### Genre Correlation Heatmap

The heatmap demonstrates the correlation between different genres, revealing interesting relationships between specific types of content. Strong positive associations, such as between TV Dramas and International TV Shows, Romantic TV Shows, and International TV Shows, can be identified.

### Most Common Words in Titles and Descriptions

Analyzing the most common words used in titles and descriptions provides insights into the themes and content focus on Netflix. Word clouds help uncover these patterns based on the titles and descriptions of Netflix’s content.

### Duration Distribution for Movies and TV Shows

Analyzing the duration distribution for movies and TV shows, the box plots reveal that most movies fall within a reasonable duration range, with few outliers exceeding approximately 2.5 hours. For TV shows, most have one to four seasons, aligning with the trend that Netflix focuses on shorter series formats.

## Conclusion

### Quantity:
Our analysis revealed that Netflix has a higher quantity of movies compared to TV shows, aligning with the expectation that movies dominate their content library.

### Content Addition:
July emerged as the month when Netflix adds the most content, closely followed by December, indicating a strategic approach to content release, potentially capitalizing on holiday seasons and summer breaks.

### Genre Correlation:
Strong positive associations were observed between various genres, such as TV dramas and international TV shows, romantic and international TV shows, and independent movies and dramas. These correlations provide valuable insights into viewer preferences and content interconnections, aiding content curation and recommendation systems.

### TV Show Episodes:
Most TV shows on Netflix have one season, suggesting a preference for shorter series among viewers. This aligns with the trend in the streaming industry towards binge-watching shorter, more focused content.

### Common Themes:
Words like love, life, family, and adventure were frequently found in titles and descriptions, capturing recurring themes in Netflix content. Understanding these common themes can be crucial for content creators and marketers aiming to resonate with viewers.

### Rating Distribution:
The distribution of ratings over the years offers insights into the evolving content landscape and audience reception. Analyzing changes in ratings distribution can provide clues about shifts in viewer preferences and content quality.

### Data-Driven Insights:
Our data analysis journey showcased the power of data in unraveling the mysteries of Netflix’s content landscape. The insights gained provide valuable information for both viewers seeking content and content creators aiming to tailor their productions to audience preferences.

### Continued Relevance:
As the streaming industry evolves, understanding these patterns and trends becomes increasingly essential for navigating the dynamic landscape of Netflix and its vast library. Continuous data analysis and adaptation to changing viewer behaviors will be crucial for Netflix's continued success in the competitive streaming market.
