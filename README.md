## Netflix_Visual_Analytics_Assignment
Netflix Data Processing and Visual Analytics project integrating Python and R. Includes data preparation, cleaning, exploratory analysis, visualization, and cross-language integration for Netflix content insights.

Author
Pascal Eliezer Okai

📘 Project Overview
This project demonstrates comprehensive data analysis, visualization techniques, and cross-language integration between Python and R for Netflix content analytics. It showcases how data professionals can handle real-world datasets, perform exploratory analysis, and create meaningful visualizations across multiple programming environments.

The workflow includes:

Importing and preprocessing Netflix content data with Python

Handling missing values and data cleaning systematically

Performing exploratory data analysis and statistical summaries

Creating visualizations for genre distribution and ratings analysis

Implementing comparative visualizations in R

Maintaining reproducible research practices

This project highlights my ability to combine analytical thinking, statistical reasoning, and visualization skills - valuable competencies for data analytics, business intelligence, and research roles.

🧩 Tasks Completed
1. Data Preparation
The Netflix dataset was imported and processed using Python, with systematic unzipping and renaming to "Netflix_shows_movies" for consistency.

2. Data Cleaning
Implemented robust missing value handling strategies:

Numerical columns: Median imputation

Categorical columns: Mode-based imputation

High-missingness features: 'Unknown' category assignment

3. Data Exploration
Performed comprehensive exploratory data analysis including:

Dataset dimensions and structure analysis

Statistical summaries for numerical variables

Frequency distributions for categorical variables

Automated column detection for Netflix-specific attributes

4. Data Visualization with Python
Created multiple visualizations using Seaborn and Matplotlib:

Most watched genres (bar charts and pie charts) - Top genres: Dramas, Comedies, International Movies

Ratings distribution (bar charts and donut charts) - Dominant ratings: TV-MA, TV-14, TV-PG

Content type analysis - Movies (71.2%) vs TV Shows (28.8%)

5. R Integration
Implemented comparative visualizations in R using ggplot2:

Ratings distribution with publication-quality styling

Cross-language validation of analytical results

6. Error Handling & Automation
Built robust error handling for:

File path management across operating systems

Automatic column detection in diverse datasets

Graceful handling of missing or corrupted data

🗂️ Project Structure
File/Folder	Description
netflix_analysis.py	Main Python script for data processing and visualization
netflix_analysis.R	R script for comparative visualizations
Netflix_shows_movies_cleaned.csv	Processed and cleaned dataset
most_watched_genres.png	Visualization of top content genres
ratings_distribution.png	Python visualization of ratings distribution
ratings_distribution_r.png	R version of ratings visualization
type_distribution.png	Movies vs TV Shows analysis
README.md	Project documentation and usage guide
📊 Key Findings from Visualizations
Genre Distribution Analysis
Top Genres: Dramas, Comedies, International Movies, Action & Adventure, Documentaries

Genre Diversity: Balanced distribution across 10 major categories

Content Strategy: Strong focus on International Movies and Dramas

Ratings Analysis
Most Common Ratings: TV-MA, TV-14, TV-PG, PG-13

Audience Coverage: Broad range from children's content (TV-Y) to mature audiences (TV-MA, R)

Content Classification: Well-distributed across age-appropriate categories

Content Type Distribution
Movies: 71.2% of Netflix catalog

TV Shows: 28.8% of Netflix catalog

Strategic Focus: Significant emphasis on movie content over series

🧠 Technologies Used
Languages: Python, R
Tools: Jupyter Notebook, RStudio, Git
Python Libraries: pandas, numpy, matplotlib, seaborn, zipfile
R Libraries: ggplot2, dplyr, readr, readxl

🚀 How to Run the Project
1️⃣ Python Workflow
Open netflix_analysis.py in your preferred Python environment

Ensure the Netflix dataset zip file is in the working directory

Run the script to execute the complete analysis pipeline:

Data loading and preparation

Data cleaning and preprocessing

Exploratory data analysis

Visualization generation

After execution, you'll get:

Cleaned dataset: Netflix_shows_movies_cleaned.csv

Multiple visualization files (.png)

2️⃣ R Workflow
Open netflix_analysis.R in RStudio

Ensure Netflix_shows_movies_cleaned.csv is in the working directory

Run the script to:

Generate comparative visualizations in R

Create publication-quality charts

Perform cross-language analysis validation

Example Output from Analysis:
text
Genre Distribution (Top 5):
- Dramas: Highest frequency genre
- Comedies: Second most popular
- International Movies: Strong global focus
- Action & Adventure: High audience appeal
- Documentaries: Educational content presence

Ratings Distribution:
- TV-MA: Most prevalent rating category
- TV-14: Strong secondary category
- TV-PG: Family-friendly content
- Diverse range covering all age groups

Content Type:
- Movies: 71.2% (Primary focus)
- TV Shows: 28.8% (Significant series collection)
🧾 Notes
Keep all files in the same directory for smooth execution

The scripts automatically handle both CSV and Excel file formats

Column detection works with common Netflix dataset structures

Visualizations are saved as high-resolution PNG files for presentations

The analysis includes both Python and R implementations for method validation

Actual visualization outputs show balanced genre distribution and clear rating patterns

🧭 Purpose
This repository is part of my growing data analytics and visualization portfolio, demonstrating comprehensive data processing, statistical analysis, and cross-language integration skills. It showcases my ability to handle complete data analysis pipelines from raw data to actionable insights, with particular emphasis on content strategy analysis for streaming platforms.

💬 Connect
📧 Email: okaipascal@gmail.com
🌍 LinkedIn: linkedin.com/in/pascal-eliezer-okai-6a9a45162
💻 GitHub: github.com/okaipascal-debug
