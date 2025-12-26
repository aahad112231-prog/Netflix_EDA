# Netflix_EDA
A simple, clear and structured EDA on netflix movies and TV shows, showcasing data cleaning, analysis and visualization
# Netflix Exploratory Data Analysis (EDA)

## Overview
Exploratory analysis of Netflix’s movies and TV shows catalog to understand content trends, growth patterns, and strategic focus over time.

## Dataset
- Source: Kaggle – Netflix Movies and TV Shows
- ~8,800 titles (Movies & TV Shows)
- Features: type, country, genre, rating, release year, date added, duration

## Objectives
- Compare Movies vs TV Shows distribution
- Analyze content growth over time
- Identify dominant genres, ratings, and countries
- Measure content age when added to Netflix

## Data Cleaning & Feature Engineering
- Handled missing values in categorical fields
- Fixed invalid rating entries
- Parsed `date_added` → year & month
- Extracted numeric duration values
- Engineered:
  - `primary_genre`
  - `duration_in_minutes`
  - `content_age = year_added - release_year`

## Key Analyses
- **Movies vs TV Shows Over Time:** Shift toward TV content post-2015
- **Top Producing Countries:** USA leads, followed by India & UK
- **Genre & Rating Distribution:** Drama and TV-MA dominate
- **Content Age Distribution:** Majority added within a few years of release

## Insights
- Netflix increasingly prioritizes TV shows over movies
- Strong focus on mature content (TV-MA, TV-14)
- Global content expansion is a core strategy
- Mix of recent and older titles ensures catalog depth

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn

## Author
**Your Name** — Aspiring Data Scientist

