# Netflix Movies & TV Shows EDA

### Project Overview
This project performs exploratory data analysis on the Netflix titles dataset to uncover content trends by type, country, release year, and genre.

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Dataset
**netflix_titles.csv**  
Contains metadata for movies and TV shows available on Netflix.

---

## Data Cleaning & Preprocessing
- Filled missing values in `director`, `cast`, `country`, `rating`, and `duration`.
- Converted `date_added` into a proper datetime format.
- Removed rows with invalid dates.
- Engineered time-based features:
  - **year_added**
  - **month_added**

---

## Exploratory Data Analysis (EDA)
### Visualizations included:
- **Movies vs TV Shows Countplot**
- **Top 10 Countries Producing Content**
- **Content Added Over the Years**
- **Top 15 Genres**

---

## Key Insights
- Netflix adds more **TV shows** than movies in recent years.
- The United States and India dominate content production.
- Genre distribution is led by Dramas, Comedies, and International films.
- Netflix significantly increased content after 2015.

---

## Skills Demonstrated
- Data Cleaning  
- Feature Engineering  
- EDA & Visualization  
- Insight Discovery  

---

## Files in This Folder
- `netflix.ipynb`
- `README.md`
