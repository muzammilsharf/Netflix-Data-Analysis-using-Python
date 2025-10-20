# Netflix Data Analysis — Country-Based Insights Using Python
**Author:** Muhammad Muzammil

This project analyzes the Netflix dataset to explore trends in movies and TV shows based on country, genre, and ratings.  
The goal is to clean, visualize, and interpret the data to understand content distribution across different regions.

### Dataset Description

The dataset was obtained from Kaggle’s Netflix Movies and TV Shows dataset and includes information such as movie/series titles, genres, ratings, directors, and release years.

**Main columns:**

- show_id — unique ID for each show
- type — Movie or TV Show
- title — name of the content
- country — country of origin
- date_added — date when added to Netflix
- release_year — release year of the content
- rating — maturity classification (e.g., TV-MA, PG-13)
- duration — duration or number of seasons
- listed_in — genres
- director, cast — creators and actors

### Data Cleaning

Before performing analysis, several cleaning steps were carried out:

- Removed duplicates to avoid repeated entries.
- Handled missing values by dropping rows with missing title, country, or release_year.
- Converted date_added to a datetime format for time-based analysis.
- Filtered the dataset to focus on major content-producing countries.
- Cleaned text fields like listed_in and director by stripping spaces and filling missing values with “Unknown”.

### Data Visualization & Insights
- Country-wise Content Distribution
- Genre Distribution
- Top Directors
- Ratings Distribution

### Tools and Libraries Used
- Python
- Pandas – data manipulation
- NumPy – numerical computations
- Matplotlib & Seaborn – visualizations
- Jupyter Notebook / VS Code – development environment

### Key Findings
- USA dominates Netflix content with over 1,875 titles.
- India and the UK follow as the next top contributors.
- Movies are more common than TV shows globally.
- Top genres include International, Drama, Comedy, and Action & Adventure.
- Most titles are rated TV-MA, TV-14, or R.
- Steven Spielberg appears as the most featured director.

### Conclusion

This project provided valuable hands-on experience in data cleaning, visualization, and analysis.
By analyzing Netflix content data, I learned how to extract meaningful insights, handle missing values, and visualize patterns effectively.
The study highlights how Netflix’s global library is dominated by American content, with growing contributions from India and the UK.
Future improvements could include analyzing user ratings, comparing multiple countries, or exploring the relationship between genres and audience ratings.
