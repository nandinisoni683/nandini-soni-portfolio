# Movies Data Analysis (Python)

**Type:** Data cleaning and EDA · **Tools:** Python, Pandas, NumPy, Jupyter · **Program:** upGrad Business Analyst

## Problem
Analyse an IMDb movies dataset to find what makes movies successful with critics and audiences.

## Approach
1. **Inspection:** checked the shape, column types and null percentages.
2. **Cleaning:** dropped irrelevant columns, then removed rows with missing values in high-null columns or with more than five NaNs. Filled missing languages, removed duplicates, and kept about 77% of rows.
3. **Analysis:**
   - Converted budget and gross to millions and added a `profit` column.
   - Found the top 10 most profitable movies.
   - Built an IMDb Top 250 (more than 25,000 votes).
   - Found the top 10 directors by mean score.
   - Ranked the most popular genre pairs.
   - Compared critic and audience favourites among lead actors.

## Key findings
- **James Cameron** has two films in the top 10 by profit.
- **Family + Sci-Fi** is the most popular genre combination.
- **Leonardo DiCaprio** leads both the critic-favourite and audience-favourite lists among the actors compared.

## Files
| File | What it is |
|---|---|
| [`movies_eda.ipynb`](movies_eda.ipynb) | Jupyter notebook with all code and outputs |
