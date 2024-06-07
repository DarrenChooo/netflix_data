# Netflix Exploratory Data Analysis

## Dataset Overview
- The dataset consists of 8809 rows and 25 columns.
- Columns from the 12th onwards are completely blank and unnecessary for the analysis, so they have been removed.

## Data Cleaning
- The dataset contains null values:
  - 30% of the `director` column is null.
  - 10% of the `cast` and `country` columns are null.
  - 10% or more null values in `date_added`, `rating`, and `duration` columns.
- Null values have been replaced with 'Unknown' to ensure data accuracy.

## Key Findings

### Content Type Distribution
- 70% of the content is Movies (6132 titles).
- 30% of the content is TV Shows (2677 titles).

### Age Rating Distribution
- The distribution of age ratings is skewed towards `TV-MA` and `TV-14`.
  - `TV-MA`: Viewed by adults and may be unsuitable for children under 17.
  - `TV-14`: Parents strongly cautioned; may not be suitable for ages under 14.
- `TV-MA` and `TV-14` are the top two ratings from the early 2000s.

### Country-wise Content Production
- **United States**: Highest content producer (2819 titles).
- **India**: Second highest content producer (972 titles), but ranks fifth in TV Show production (79 titles).
- **TV Show 2nd-4th**:
  - United Kingdom: 213 titles.
  - Japan: 169 titles.
  - South Korea: 159 titles.
- **Movies 2nd-5th**:
  - India: 893 titles.
  - United Kingdom: 206 titles.
  - Canada: 172 titles.
  - Spain: 97 titles.

### Genre Distribution
- **Movies**:
  - Drama: 362 titles.
  - International Movies: 362 titles.
  - Documentaries: 359 titles.
  - Stand-Up Comedy: 334 titles.
- **TV Shows**:
  - Kids' TV: 220 titles.
  - International TV Dramas: 121 titles.
  - Crime TV Shows: 110 titles.

### Average Duration and Seasons
- **Movies**:
  - Average duration: 99.58 minutes.
  - In the 1960s to 1970s, the average duration was higher at 150 minutes.
  - Duration has declined over the years from the 1960s to the 2020s.
- **TV Shows**:
  - Average number of seasons: 1.76.
  - Most common number of seasons: 1 (1750/2677 titles).
  - In the 1970s to 1990s, the average number of seasons was higher at roughly 4 seasons.
  - Number of seasons has declined the years from the 1970s to the 2020s.

## Conclusion
This report provides an exploratory analysis of the Netflix dataset, highlighting key trends and insights about content type distribution, age ratings, country-wise production, genre distribution, and the average duration and seasons of Movies and TV Shows.

