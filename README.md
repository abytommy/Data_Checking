# YOUTUBE ANALYSIS

## Table Of Content
- [Project Overview](#project-overview)
- [Data source](#data-source)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning/preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results/findings)
- [Recommendation](#recommendation)
- [Limitations](#limitations)
  
## Project Overview
This data analysis project provides insights into the YouTube performance of different influencers around the world.


![youtube pic](https://github.com/user-attachments/assets/cda4c954-b19d-4ee2-bd28-3df2281b8bd2)


#### Data source
The primary dataset used for this project is "youtube_data_united-states" gotten from Kaggle.

#### Tools
- Excel(Data Cleaning)
- Power Bi(Data Analysis, Creating Report)

#### Data Cleaning/Preparation
We performed the following tasks for the preparation phase:

1. Data loading.

2. Handling missing values

3. Cleaning data.

#### Exploratory Data Analysis

This involved exploring the youtube dataset to answer questions, such as:

1. What is the highest channel name with the most reach?

2. Which Channel has the highest engagement reach?

3. Total channels by Videos?

4. Channel Total views?

#### Data Analysis
Using the power query I replaced some values to calculate better.

Created a Dax function
```powerbi
COUNTA('youtube_data_united-states'[NAME])
```

#### Results/Findings

The Analysis Results are Summarised as follows:

- Top Channel by Potential Reach: T-Series (India) with 70.2 million.

- Highest Engagement Rate: CarryMinati (India) with an ER of 0.092.

- Total Channels: 100 channels.

- Total Potential Reach: Approximately 1.4 billion.

Most channels are from India and the US, with limited influence on specific topics despite their massive reach.

#### Recommendation

Based on the analysis, we recommend the following actions:

- Engage High-Reach Channels: Convert large audiences (e.g., T-Series) into active engagement with interactive content.

- Boost Engagement: Increase viewer interaction for channels like SET India through collaborations and targeted campaigns.

- Prioritize High-Engagement Influencers: Focus on influencers like CarryMinati for partnerships due to strong engagement.

- Explore New Markets: Expand into growing regions like Brazil and Mexico for global reach.

- Promote Topic-Specific Content: Encourage content with a clear focus to improve brand targeting and audience engagement.

#### Limitations

- Low Engagement Data: Most channels have an engagement rate of zero, limiting insights into actual audience interaction and effectiveness.

- Lack of Topic Influence: Many channels are marked as "Didn't Influence," making it difficult to assess their specific impact or relevance in niche areas.

- Geographic Bias: The dataset is dominated by channels from India and the US, which may not reflect trends in other regions.

- Incomplete Information: Several channels lack country or topic details, reducing the accuracy of regional and content-specific analysis.

- Potential Reach vs. Actual Impact: High reach does not necessarily translate into influence or engagement, limiting the usefulness of potential reach as a sole metric.


