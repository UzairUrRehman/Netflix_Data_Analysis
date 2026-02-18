# Netflix Movies & TV Shows – Data Analysis Project

A **data-driven Exploratory Data Analysis (EDA) project** implemented in **Python**, analyzing content distribution, genres, countries, release trends, and ratings

---

## Overview
This project implements an **Exploratory Data Analysis (EDA)** on Netflix Movies & TV Shows data to uncover patterns in content types, production countries, genres, release trends, ratings, and director contributions.  
The analysis focuses on understanding how Netflix content is distributed globally and how content production has evolved. 
A structured EDA workflow is followed to generate insights using Python data analysis and visualization libraries.

---

## Core Features
- Comparison of Movies vs TV Shows count  
- Identification of top countries producing Netflix content  
- Genre frequency analysis  
- Year-wise content release trend analysis  
- Distribution analysis of content ratings  
- Director-wise content contribution analysis  
- Multiple visualizations to support analytical findings  

---

## Technology Stack
- **Language:** Python  
- **Libraries Used:** NumPy, Pandas, Matplotlib, Seaborn  
- **Execution Environment:** Jupyter Notebook   

---

## Application Mechanics
- Data is loaded and cleaned using **Pandas**  
- Grouping, filtering, and aggregation are applied to analyze content trends  
- Visualizations are created using Matplotlib and Seaborn, including:
  - Bar chart for Movies vs TV Shows count  
  - Horizontal bar chart for top 10 content-producing countries  
  - Pie chart for content rating distribution  
  - Line plot for number of releases per year  
  - Heatmap for country vs genre frequency  
- The analysis answers the following questions:
  - Total number of Movies vs TV Shows  
  - Top 10 countries producing Netflix content  
  - Most common genre on Netflix  
  - Years with the highest number of releases  
  - Distribution of content ratings  
  - Directors with the most titles  

---

## Key Insights
- Movies dominate Netflix compared to TV Shows, indicating a strong focus on film content  
- International Movies and Dramas are the most common genres, appealing to a global audience  
- The United States produces the most content, followed by India and the United Kingdom  
- Content releases peaked in 2018, reflecting rapid platform growth  
- Most titles are rated TV-MA and TV-14, targeting mature and teenage audiences  
- A small number of directors contribute a large volume of titles, indicating content specialization  

---

## Dataset Information
- **Dataset Name:** Netflix Movies and TV Shows  
- **Source:** Kaggle  

---

## Project Structure

- **netflix-movies-tvshows-eda/**  
  - `Netflix_Movies_TV_Shows_EDA.ipynb` → Jupyter Notebook containing the complete EDA  
  - `netflix_titles.csv` → Dataset used for analysis  
  - `README.md` → Project documentation  
