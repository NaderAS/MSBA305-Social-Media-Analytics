This project is divided into two major parts focusing on Reddit and Twitter analytics, machine learning modeling, and manual knowledge graph construction using Neo4j.

## 📚 Project Overview

This repository contains code, analysis, and manually constructed graph work for:

### Part 1: Knowledge Graph Construction

- Manually created sample data (posts, comments, authors, topics)
- Built a Neo4j Knowledge Graph using the generated data
- Visualized relationships between:
  - Posts
  - Authors
  - Topics
- Performed basic graph analysis:
  - Node degrees
  - Community detection
  - Centrality metrics

### Part 2: Predicting Social Media Engagement

- Scraped Reddit posts and comments using the PRAW API
- Extracted Twitter posts for broader engagement analysis
- Engineered features: posting hour, day of week, content type (text, image, video)
- Conducted exploratory data analysis (EDA)
- Built machine learning models:
  - Linear Regression 
  - Random Forest Regression
- Tracked experiments using MLflow
- Optimized large dataset joins with PySpark partitioning

## 📁 Project Structure
```
MSBA305-Social-Media-Analytics/
├── part1_neo4j/
│   ├── cypher_scripts/
│   │   └── neo4j_part_1.ipynb
│   └── screenshots_neo4j/
│       ├── Content Creation Flow.png
│       ├── Engagement with Topics.png
│       ├── FOLLOWS Network.png
│       ├── Topic-Post-Platform.png
│       ├── User Community Network.png
│       └── topic_relationships.png
├── part2_spark_scraping/
│   ├── notebooks/
│   │   ├── Twitter_scraping.ipynb
│   │   ├── reddit_scraping.ipynb
│   │   └── spark_social_media_analytics.ipynb
│   ├── reddit_data/
│   │   ├── reddit_post_comments.csv
│   │   └── reddit_posts_df.csv
│   └── twitter_data/
│       ├── twitter_data_science.csv
│       └── twitter_data_science_sentiment.csv
├── part3_analysisdocument.pdf
└── README.md
```

## 🚀 Technologies Used

- Python (Pandas, PRAW, Tweepy, Matplotlib, Seaborn)
- PySpark for scalable data processing
- Databricks for distributed analytics
- MLflow for model management
- Neo4j for graph database visualization

## 📊 Key Deliverables

- **Manually constructed Neo4j Knowledge Graph**
- **Time Series Analysis:** Engagement trends by day and hour
- **Engagement Prediction Models:** Linear and Random Forest regressions
- **PySpark Performance Optimization:** Repartitioning and coalescing techniques
- **Visualizations:** Content type comparison, hourly patterns, feature importances

## 🧠 Authors

- Maisoon Abo Fakher  
- Joulnar Abou Chakra  
- Nader Abdul Salam  
- Abdallah Asaad  
- Nivine Manasfi  

**Advisor**: Dr. Ahmad El Hajj  
**Course**: MSBA 305 - Data Processing

## 📄 License

This project is developed for academic purposes as part of the MSBA 305 coursework at the American University of Beirut (AUB).
