# Twitter Analytics Dashboard

## Project Overview
This Power BI dashboard provides comprehensive insights into Twitter engagement metrics, focusing on various aspects of user interaction and tweet performance. The project aims to visualize and analyze Twitter data to derive meaningful insights for social media strategists and content creators.

## Features

### 1. Click Distribution for High-Impression Tweets
- Pie chart showing the proportion of total clicks (URL, user profile, hashtag) for tweets with >500 impressions
- Drill-down functionality to view specific click types for each tweet

### 2. Media Engagement vs. Views Analysis
- Scatter plot examining the relationship between media engagements and views
- Filters:
  - Tweets with >10 replies
  - Time range: 12 PM to 6 PM
  - Odd-numbered tweet dates
  - Tweet word count <50
- Highlights tweets with >5% engagement rate

### 3. Click Types by Tweet Category
- Clustered bar chart breaking down URL, user profile, and hashtag clicks by tweet category
- Includes tweets with at least one interaction type
- Filters:
  - Time range: 3 PM to 6 PM
  - Even-numbered tweet dates
  - Tweet word count <40

### 4. Monthly Average Engagement Rate Trend
- Line chart showing average engagement rate trends over months
- Separate lines for tweets with and without media content
- Filters:
  - Time range: 3 PM to 6 PM
  - Even-numbered tweet engagement
  - Odd-numbered tweet dates

### 5. Engagement Rate Comparison: App Opens vs. No App Opens
- Comparison of engagement rates for tweets with and without app opens
- Filters:
  - Weekdays between 9 AM and 5 PM
  - Time range: 12 PM to 6 PM
  - Even-numbered tweet impressions
  - Odd-numbered tweet dates
  - Tweet word count <40

## How to Use
1. Clone this repository
2. Open the .pbix file using Power BI Desktop
3. Refresh the data source if necessary
4. Interact with the visualizations to explore the Twitter analytics data

## Requirements
- Power BI Desktop (latest version recommended)
- Twitter data source (connection details in the .pbix file)

## Contributing
Contributions to improve the dashboard are welcome. Please fork the repository and submit a pull request with your proposed changes.
