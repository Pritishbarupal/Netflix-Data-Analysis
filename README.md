
# **Netflix Data Analysis**

This repository explores a dataset of Netflix movies and TV shows, uncovering interesting trends and patterns in content production and user preferences of genres.

## Content Analysis: Techniques and Libraries
The exploration of the Netflix data involved a multi-step process that leveraged powerful Python libraries for data manipulation, analysis, and visualization. Here's a breakdown of the key techniques employed:
#### Data Cleaning and Preprocessing:
- Libraries: Pandas
- Tasks: Handled missing values, Identified and corrected inconsistencies in data formatting (date format).
#### Exploratory Data Analysis (EDA):
- Libraries: Pandas, NumPy, matplotlib, seaborn (optional)
- Content Type Analysis: Calculated the frequency of movies and TV shows using Pandas' .value_counts() method.
- Production Origin Analysis: Analyzed the distribution of production countries using Pandas' .value_counts() method to identify top producers.
- Target Audience Analysis: Examined the frequency of content rating categories (e.g., MA, TV-PG) using Pandas' .value_counts() method.
- Production Year Analysis: Investigated the distribution of content release years using Pandas' .value_counts() method to pinpoint the year with the most content.
- Genre Popularity Analysis: Counted the occurrences of genres using Pandas' .value_counts() method to determine the most popular ones.
- Visualization: Created charts and graphs (e.g., bar charts, pie chart) using matplotlib and seaborn to visually represent the findings from the above analyses. This enhances the clarity and impact of the results.

## Key Findings:
- Netflix has more movies than TV shows
- Most number of movies and TV shows are produced by United States ,followed by India holding second position
- A large proportion of content on Netflix is for MA (Matured Auudience)
- 2018 is the year during which Netflix produced a large count of content as compared to the other years.
- Till 2018 the Content produced was in increasing order but after COVID Year (2020), we can observe the declination.
- International Movies and Drama are the most popuplar Genres on Netflix
