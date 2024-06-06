## README

# YouTube Trending Videos Data Analysis

Welcome to the YouTube Trending Videos Data Analysis project! This repository contains a Python project that uses the Google YouTube API to collect and analyze data on trending YouTube videos. The goal of this analysis is to uncover insights and patterns that explain what makes a video trend on YouTube.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Data Collection](#data-collection)
- [Analysis](#analysis)
  - [Frequency Distribution](#frequency-distribution)
  - [Correlation Matrix](#correlation-matrix)
  - [Category Analysis](#category-analysis)
  - [Engagement Metrics](#engagement-metrics)
  - [Video Length Analysis](#video-length-analysis)
  - [Publish Hour Distribution](#publish-hour-distribution)
- [Conclusions](#conclusions)
- [Requirements](#requirements)
- [Usage](#usage)
- [License](#license)

## Introduction

This project leverages the Google YouTube API to gather data on trending videos and perform a comprehensive analysis. By examining various metrics such as views, likes, comments, video length, and publish hour, we aim to identify the key factors that contribute to a video's popularity on YouTube.

## Features

- **Frequency Distribution**: Analysis of the count distribution of views, likes, and comments.
- **Correlation Matrix**: Examination of the correlation between different engagement metrics.
- **Category Analysis**: Visualization of the count of videos per category and average engagement metrics by category.
- **Video Length Analysis**: Scatter plot of video length versus view count and bar chart of engagement metrics by duration range.
- **Publish Hour Distribution**: Count plot of the distribution of videos by the hour they were published.
- **Conclusions**: Insights and patterns derived from the data analysis.

## Data Collection

The data is collected using the Google YouTube API. Specifically, we fetch data on trending videos, including details such as views, likes, comments, video length, category, and publish time.

## Analysis

### Frequency Distribution

We analyze the frequency distribution of views, likes, and comments to understand the general engagement patterns of trending videos.

### Correlation Matrix

A correlation matrix is created to identify the relationships between different engagement metrics such as views, likes, and comments.

### Category Analysis

- **Category Counts**: Bar chart showing the number of trending videos in each category.
- **Average Engagement Metrics**: Bar charts displaying the average views, likes, and comments for each category.

### Engagement Metrics

Detailed analysis of engagement metrics including views, likes, and comments, broken down by video category.

### Video Length Analysis

- **Scatter Plot**: Visualizing the relationship between video length and view count.
- **Engagement by Duration Range**: Bar chart showing average engagement metrics for different video length ranges.

### Publish Hour Distribution

A count plot showing the distribution of trending videos by the hour of the day they were published, providing insights into optimal publish times.

## Conclusions

Based on the analysis, we provide insights into what factors contribute to a video becoming trending on YouTube. These include:

- Categories with the highest engagement
- Optimal video lengths
- Best times to publish videos
- Correlations between different engagement metrics

## Requirements

To run this project, you need the following Python packages:

- `google-api-python-client`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`

You can install the required packages using:
```sh
pip install google-api-python-client pandas numpy matplotlib seaborn scipy
```

## Usage

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/SaiDeepak16/YouTube_Data_Collection_and_Analysis.git
   ```

2. **Set Up API Key**:
   Obtain a YouTube API key from the [Google Developers Console](https://console.developers.google.com/), and replace `API_KEY` in your code with your actual key.



---

By following the above steps, you will be able to replicate the analysis and visualize the data to gain insights into the factors that make a video trend on YouTube. Thank you for using this repository! If you have any questions or feedback, feel free to open an issue or submit a pull request.
