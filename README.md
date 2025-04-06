## MOVIES DATA ANALYSIS AND CORRELATION

# Overview
This project involves bit of Exploratory Data Analysis (EDA), data cleaning of the Movie Industry dataset from kaggle, the primary goal is to analyze the dataset and uncover correlations between various attributes, with exploring the relationships between budget, gross revenue, movie production companies, and much more.

# 📁 About the Dataset

- **Source**: Kaggle (The Movie Dataset)
- **Entries**: ~5,000 movies
- **Features**:
  - `movie name`: Title of the movie
  - `rating`: MPAA rating (PG, PG-13, R, etc.)
  - `genre`: Movie genre(s) such as Action, Drama, etc.
  - `year of release`: Year the movie was released
  - `IMDb score`: IMDb rating on a scale of 1–10
  - `viewer votes`: Number of votes received by viewers
  - `director`: Name of the director
  - `writer`: Name of the writer(s)
  - `star`: Lead actor/actress
  - `country`: Country of production
  - `budget`: Budget of the movie
  - `gross revenue`: Worldwide box office gross
  - `production company`: Studio or company behind the movie
  - `runtime`: Duration of the movie in minutes

---

## 📊 Visualizations & Insights

### 🎯 1. Budget vs Gross Revenue  
This scatter plot reveals a strong positive correlation between a movie's budget and its gross revenue. However, the data also shows outliers—low-budget films that made huge profits, and high-budget films that failed to recover costs. This suggests that while budget is important, it's not the only factor influencing success.

### ⭐ 2. IMDb Score vs Viewer Votes  
The data shows a moderate positive relationship between IMDb rating and number of votes. Movies with higher IMDb scores typically receive more attention and engagement. However, some cult classics with high ratings received fewer votes, indicating a niche but passionate audience base.

### 🎥 3. Genre Popularity Over Time  
Bar plots and count plots help visualize how certain genres have trended over the years. Action, Drama, and Comedy remain dominant, while genres like Documentary and Musical show sporadic but notable success depending on era or societal interest.

### 🧑‍🎓 4. Director and Star Impact  
Using group-by analysis and aggregation, we examined the influence of directors and lead stars on movie performance. Directors with consistent hits can boost a movie's chances, and some stars appear in multiple high-grossing or high-rated films—indicating their draw at the box office.

### ⏱️ 5. Runtime vs IMDb Score  
A scatter plot between runtime and IMDb score shows no strong linear relationship. Both short and long films can be rated highly, depending on content quality and audience preference.

### 📈 6. Correlation Heatmap
![](https://imgur.com/F8pdckB)
A heatmap provided a comprehensive view of how numerical features relate. Strong positive correlations were found between:
- Budget and Revenue  
- Viewer Votes and IMDb Score  
- Budget and Vote Count  
Interestingly, runtime showed weak correlation with most metrics.
