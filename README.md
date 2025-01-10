# YouTube Usage Analysis and Its Relation with Daily Life

**Author:** Ozan Kaçmaz (32123)

## Table of Contents

- [Motivation](#motivation)
- [Data Set](#data-set)
- [Data Processing](#data-processing)
- [Data Analysis](#data-analysis)
- [Conclusion](#conclusion)
- [License](#license)

## Motivation

In the modern era, social media has become an indispensable part of daily life. Every day, we encounter numerous images and videos on the internet, each differing in the platforms we use to access them. For me, YouTube stands out as the most significant social media platform among others. The reason is straightforward: while it is possible to meet individuals who do not use Instagram, Twitter, Reddit, or other social media platforms, it is highly unlikely to encounter someone who does not use YouTube. In other words, the probability of meeting a person who does not use YouTube is lower than the probability of meeting someone who doesn't use Instagram, Twitter, and so forth.

This observation is supported by data from [globalmediainsight.com](https://www.globalmediainsight.com), which reports that YouTube has over **2.7 billion monthly active users** as of November 2024. Additionally, only Facebook surpasses YouTube in terms of active user numbers. These statistics, combined with my personal experiences, highlight the pervasive influence of YouTube. Whether for educational purposes—such as researching a topic—or for entertainment, like watching videos, YouTube is a go-to platform.

This widespread usage led me to reflect on my own interaction with YouTube. I began to question how I utilize the platform:

- How many videos do I watch in a day average?
- What topics do I engage with the most?
- How many hours do I spend actively watching YouTube each day?
- Can I build a machine learning model to classify categories of the videos.
- Which supervised learning algorithm is best in terms of correctly classifying categories?
  
These questions motivated me to analyze my YouTube usage data to seek answers and gain a deeper understanding of my viewing habits. Furthermore, I aim to find relations between my YouTube usage and daily life activities.

## Data Set

I downloaded my YouTube data from [Google Takeout](https://takeout.google.com/). The exported data includes the following components:

- **Watch History:** A record of all the videos I have watched on YouTube.


The data is provided in JSON format. To prepare the data for analysis, I plan to perform the following preprocessing steps:

## Data Processing

1. **Data Cleaning:** Remove any duplicate entries and irrelevant data points.
2. **Data Transformation:** Convert JSON files to CSV format for easier manipulation using data analysis tools.
3. **Data Integration:** Combine different data components to create a comprehensive dataset for analysis.

## Data Analysis

For the analysis, I will use Python and its data analysis libraries like `pandas` and `matplotlib` to visualize my YouTube usage patterns. This data will help answer the following research questions:

1. **Do I watch more videos or listen to music on YouTube?**
2. **What are the most common topics I engage with?**
3. **How many hours do I spend actively watching YouTube each day?**
4. **Do I tend to use YouTube more in the mornings or evenings?**
5. **How does my YouTube usage correlate with my daily life activities?**

### Tools and Technologies

- **Programming Language:** Python
- **Libraries:**
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for data visualization
  - `numpy` for numerical operations
  - `nltk`, `spacy` for text preprocessing
  - `ngrok` for local machine simulation
  - `regex`
  - `skilearn`
  - `youtube-dlp` for getting metadatas of videos
  

### Methodology

1. **Data Collection:** Export YouTube data from Google Takeout.
2. **Data Preprocessing:** Clean, transform, and integrate the data.
3. **Exploratory Data Analysis (EDA):** Identify patterns and trends in the data.
4. **Visualization:** Create charts and graphs to illustrate findings.
5. **Correlation Analysis:** Examine the relationship between YouTube usage and daily activities.
6. **Youtube Recommendation App** I will build an recommendation system using my own dataset. It will recommend video based on the title.

## Conclusion

Through this analysis, I aim to gain insights into my YouTube consumption habits and understand how they intersect with my daily routines. This project not only provides personal reflections but can also serve as a case study for understanding broader social media usage patterns.


#update for data collecting and analysis
#update again
#update multithread
#update regression
#updated somecode parts
##Commiting because I am working on for this project. for the record.
