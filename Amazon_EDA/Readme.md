## **Project Summary**
---

This project aims to analyze Amazon Prime TV Shows and Movies using two datasets: **titles.csv** and **credits.csv**.

The goal is to uncover insights that can drive business decisions, such as content acquisition, audience targeting, and content performance evaluation.

titles.csv contains **9,871** records with details about movies and TV shows, including title, type, description, release year, genres, runtime, IMDb and TMDB scores, and age certification.

credits.csv contains **124,235** records related to actors, characters, and roles in various movies and shows.
The primary objectives of this analysis include:

#### **Understanding content trends** – Analyzing genre distribution, popular countries, and content ratings.

#### **Assessing content performance** – Identifying high-rated movies and shows based on IMDb and TMDB scores.

#### **Detecting gaps in content** – Finding missing values in IMDb/TMDB ratings and age certifications.

#### **Outlier analysis**– Identifying anomalies in runtime, ratings, and popularity.

#### **Visualizing key patterns**– Creating graphs for effective data representation.


--------
This Dataset was created to analyse all shows available on Amazon Prime Video allowing us to extract valuable insights such as:

**Content Diversity**: What genres and Categories dominate the platform

**Regional Availability**: How does Content distribution vary across different regions.

**Trend's Over Time**: How has Amazon Prime's content library evolved

**IMDB's Rating and Popularity**:What are the highest-rated or most popular shows on the platform

By analysing the dataset businesses ,content creators and data Analysts can uncover the key trends that influence subscription growth and user engagement ,and content investment strategies in the streaming industry.

-------

## **Business Objective**
---
Amazon Prime Video aims to enhance content recommendations and acquisitions by leveraging data analytics. The insights gained from this analysis will help in:

**Identifying top-performing genres** to focus on content that attracts high audience engagement.

**Understanding regional content preferences**  for better localization and expansion strategies.

**Improving content filtering** by analyzing IMDb and TMDB scores for better user recommendations.

**Evaluating actor impact** on movie/show success, helping in better casting decisions.

-------
#### We have merged titles and credits dataset

**We discovered that there are lot of missing values and Duplicate values**

**DataType Change Seasons(float) to Integer**

**Leaving the Duplicates as each feature has different value Thus unique**

**Drop few Null and missing values and imputed majority of them in 'character' ,'seasons','age_certfication','production_countries'**

**Remove the Outliers in the numerical columns except in imdb_votes as it highly skewed feature so used log transformation  and now we have very few outliers**

**After Removing Outliers we have only 86,363 rows and 19 columns**

**Insights from the Violin Plots (After Outlier Removal)**:

**Runtime**:

1.Most movies and shows have runtimes clustered around 60-120 minutes.
The distribution is fairly symmetrical after removing extreme durations.
IMDB Score:

2.Scores are concentrated between 5 and 7, suggesting most titles receive average ratings.
Few very low or very high-rated entries remain after outlier removal.
IMDB Votes (Log-Transformed):

3.The distribution is now smoother and closer to normal.
Most titles receive a modest number of votes, with a long tail of highly popular titles.
TMDB Popularity (Log-Transformed):

4.Similar to IMDB votes, popularity is right-skewed but better normalized after the log transformation.
Most titles have low-to-moderate popularity scores.
TMDB Score:

Scores are tightly clustered between 5 and 7, showing a bias toward mid-range ratings.

**Thus making the Dataset ready to Visualise**
---------

### **Comprehensive Solution to the Business Objective**  

1. **Prioritize High-Engagement Content Types:**  
   Focus on content types with **proven audience engagement** (e.g., TV series, mini-series) to **boost viewer retention** and **streaming hours**.  

2. **Focus on Popular Genres:**  
   Invest in **consistently popular genres** like **Drama, Action, and Thriller**, while **monitoring emerging combinations** (e.g., Sci-Fi + Mystery) to **capture evolving audience preferences**.  

3. **Optimize Runtime for Higher Engagement:**  
   Target an **optimal runtime range** (90-120 mins for movies, 30-60 mins for episodes) to **balance engagement** without viewer fatigue.  

4. **Leverage Correlation Insights:**  
   Use **data-driven correlations** (e.g., higher IMDb scores aligning with higher TMDB popularity) to **prioritize quality content** that resonates across platforms.  

5. **Surface Hidden Gems:**  
   Identify and promote **underrated, high-quality content** with **strong ratings but low visibility**, increasing engagement without heavy acquisition costs.  

6. **Personalized Recommendations:**  
   Implement **personalized algorithms** using viewer behavior and genre preferences to **enhance user satisfaction** and **reduce churn**.  

7. **Target Release Timing:**  
   Align content releases with **seasonal demand** (e.g., Horror during Halloween, Romance around Valentine’s) to **maximize viewership spikes**.  

8. **Curate Binge-Worthy Content:**  
   Emphasize **serialized storytelling** and multi-season content to **encourage binge-watching**, increasing platform stickiness and viewer loyalty.  

This **data-driven, audience-centric** strategy will **maximize engagement**, **enhance content value**, and **drive platform growth**.

