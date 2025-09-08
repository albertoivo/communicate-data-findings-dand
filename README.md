# Ford GoBike System Data Analysis

## Project Overview

This project explores the Ford GoBike system data from February 2019, focusing on understanding trip patterns, user demographics, and usage behaviors in the San Francisco Bay Area bike-sharing system. The analysis follows a comprehensive data science approach, from exploratory data analysis to explanatory visualizations that tell a compelling story about urban mobility patterns.

## Dataset

**Source**: Ford GoBike System Data (February 2019)  
**Size**: 183,412 trips with 16 variables  
**Coverage**: San Francisco Bay Area, California  
**Time Period**: February 2019

### Key Variables:
- **Trip Duration**: Duration of each trip in seconds
- **Start/End Times**: Timestamp data for trip timing
- **Station Information**: Start and end station names and IDs
- **User Demographics**: Birth year, gender, user type
- **User Types**: Subscriber vs. Customer classification
- **Geographic Data**: Station locations and bike IDs

### Data Quality:
- **Original Records**: 183,412 trips
- **After Cleaning**: 175,068 valid records
- **Missing Values**: Successfully handled 8,265 missing demographic records
- **Outlier Treatment**: Removed unrealistic ages (>90 years) and extreme trip durations

## Key Findings

### 📊 User Demographics
- **Primary User Base**: Young to middle-aged adults (25-45 years)
- **Peak Age Group**: 30-35 years old
- **User Distribution**: 85% Subscribers vs. 15% Customers
- **Gender Patterns**: Notable differences in trip duration between genders

### 🚴‍♂️ Trip Patterns
- **Typical Duration**: 5-15 minutes (highly right-skewed distribution)
- **Usage Purpose**: Primarily short-distance urban commuting
- **Peak Hours**: Clear commuting patterns with distinct subscriber vs. customer behaviors
- **Efficiency**: High bike turnover supporting fleet optimization

### 🔍 Behavioral Insights
- **Subscribers**: Shorter, more consistent trip durations (commuting focus)
- **Customers**: Longer, more variable trips (leisure/tourist usage)
- **Age Correlation**: Moderate positive correlation between age and trip duration
- **Consistency**: Subscription preference remains stable across all age groups
