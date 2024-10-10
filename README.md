# DAI-101-assignment

Repository containng EDA based Jupyter notebook for DAI-101 Assigment 1
Submission by Advika Sinha 23117010

# F1 Drivers Dataset Analysis

## Exploratory Data Analysis & Data Cleaning Report

### Table of Contents

1. [Dataset Overview](#dataset-overview)
2. [Data Cleaning Process](#data-cleaning-process)
3. [Exploratory Data Analysis](#exploratory-data-analysis)
4. [Key Insights](#key-insights)

### Dataset Overview

The Formula 1 Drivers Dataset spans from 1950 to 2021, containing comprehensive statistics and information about F1 drivers throughout the sport's history. This analysis explores various aspects of driver performance, career longevity, and trends in the sport.

#### Key Features:

- Driver demographics (nationality, age)
- Performance metrics (wins, podiums, pole positions)
- Career statistics (starts, championships)
- Temporal data (active years, career span)

### Data Cleaning Process

#### 1. Handling Missing Values

- Identified and addressed NULL values in crucial columns
- Implemented appropriate strategies for different types of missing data

#### 2. Data Type Corrections

- Ensured consistency in numerical columns (int/float)
- Standardized string columns (capitalization, spacing)

### Exploratory Data Analysis

#### 1. Nationality Distribution

<img src="/media/choropleth.png" alt="Top 10 Driver Nationalities">

Key findings:

- Distribution of national representation over time and across drivers

#### 2. Performance Metrics Analysis

<img src="/media/corrmap.png" alt="Correlation Matrix of Performance Metrics">

Explored relationships between:

- Wins and podiums
- Pole positions and race wins
- Career length and total points

### Key Insights

1. **Performance Trends**:

   - Strong correlation between pole positions and wins

2. **Demographic Shifts**:
   - Increasing diversity in driver nationalities
   - Changes in average driver age over decades

### Further Analysis Opportunities

- Predictive modeling for driver performance
- Comparative analysis across different eras
- Team impact on driver performance
