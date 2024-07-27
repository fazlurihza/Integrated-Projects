### Project Description

I am working as an analyst at "Ice," an online store specializing in video games worldwide. The goal is to identify patterns that determine a game's success based on data from 2016. This analysis will help plan the advertising campaigns for 2017.

**Objective:** Analyze data from 2016 to identify successful games, plan effective marketing strategies, and forecast potential hits for the upcoming year.

**Instructions:**

1. **Data Preparation:**
   - Load and examine the dataset from `games.csv`.
   - Rename columns to lowercase and convert data types as needed.
   - Handle missing values and TBD (to be determined) entries appropriately.
   - Calculate total global sales for each game and add this to the dataset.

2. **Data Analysis:**
   - Analyze game releases by year and determine the significance of the data.
   - Examine sales variations across platforms, identify top-performing platforms, and observe trends in platform popularity.
   - Analyze sales by platform and genre, create boxplots for global sales by platform, and assess the impact of user and critic reviews on sales using scatter plots and correlation analysis.

3. **User Profiling:**
   - For each region (NA, EU, JP), identify the top 5 platforms and genres. Analyze market share variations and assess the impact of ESRB ratings on sales.

4. **Hypothesis Testing:**
   - Test the following hypotheses:
     - The average user rating for Xbox One and PC platforms is the same.
     - The average user rating for Action and Sports genres differs.
   - Formulate null and alternative hypotheses and select an appropriate significance level.

5. **Conclusion:**
   - Summarize findings and insights in a Jupyter Notebook, including code and explanations.

**Data Description:**
- **Name:** Game title
- **Platform:** Gaming platform (e.g., Xbox, PlayStation)
- **Year_of_Release:** Release year
- **Genre:** Game genre
- **NA_sales:** Sales in North America (in million USD)
- **EU_sales:** Sales in Europe (in million USD)
- **JP_sales:** Sales in Japan (in million USD)
- **Other_sales:** Sales in other regions (in million USD)
- **Critic_Score:** Critic reviews score (0-100)
- **User_Score:** User reviews score (0-10)
- **Rating:** ESRB rating

This project aims to uncover successful game patterns and guide the marketing strategy for the upcoming year.
