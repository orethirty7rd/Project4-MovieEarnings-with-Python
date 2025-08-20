# Movie Data Analysis

This project explores the relationship between different movie attributes (such as budget, gross earnings, studio names, and votes) using Python for data cleaning, statistical analysis, and visualisation.  

## Project Overview
The goal was to clean and standardise a dataset of movies, then investigate which factors have the strongest impact on **gross earnings**.

### Steps Taken
1. **Data Cleaning & Standardisation**  
   - Removed inconsistencies and formatted the dataset for analysis.  

2. **Exploratory Analysis**  
   - Used scatter plots with regression lines to identify potential correlations.  

3. **Correlation Analysis**  
   - Applied **Pearson correlation** to measure the strength of relationships.  
   - Visualised results with **heatmaps** for clearer insights.  

4. **Key Findings**  
   - **Budget** has a **strong positive correlation** with gross earnings.  
   - **Votes** (audience engagement) also show a strong relationship with gross earnings.  
   - **Studio names** had a weaker influence, but categorical data was successfully converted to numerical form to test the correlation.  

## Visualisations
- Scatter plots with trend lines (budget vs. gross earnings).  
- Heatmaps showing correlation across multiple features.  

## Tools & Libraries
- **Python** (Jupyter Notebook)  
- **Pandas** – data cleaning and manipulation  
- **NumPy** – numerical operations  
- **Matplotlib & Seaborn** – visualisation  
- **SciPy** – Pearson correlation  

## Insights
The analysis highlights that while a movie’s studio has some impact, **budget and audience votes** are far stronger indicators of its financial performance.  

## Next Steps
- Expand analysis with additional variables (e.g., genre, runtime).  
- Build a regression model to predict gross earnings based on budget and votes.  
