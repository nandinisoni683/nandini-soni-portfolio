# RSVP Movies: IMDb SQL Case Study

**Type:** SQL analysis · **Tools:** MySQL · **Program:** upGrad Business Analyst

## Problem
RSVP Movies, an Indian production house, plans to make a film for a global audience. Using an IMDb database (tables: movie, genre, ratings, names, director_mapping, role_mapping), recommend the genre, directors, actors and production partners for the next project.

## Approach
The script answers 24 business questions in three segments:
1. **Data exploration:** row counts, null checks, release trends by year and month, and genre counts.
2. **Ratings analysis:** top-rated movies, median rating distribution, hit movies by production house, and German vs. Italian votes.
3. **Talent analysis:** top directors in the top genres, top actors and actresses by rating, top production houses by votes, and a classification of thriller movies by rating.

SQL used: `JOIN`s across 6 tables, `GROUP BY`/`HAVING`, CTEs, window functions (`RANK`, `DENSE_RANK`, `ROW_NUMBER`) and `CASE` classification.

## Key findings
- **Drama** is the most-produced genre, and **Thriller** ranks in the top 3.
- **March** has the most releases.
- **James Mangold** stands out among directors in the top genres.
- **Marvel Studios** leads production houses by votes.
- **Taapsee Pannu** tops Hindi-film actresses with an average rating of 7.74.

## Files
| File | What it is |
|---|---|
| [`rsvp_imdb_analysis.sql`](rsvp_imdb_analysis.sql) | All queries with comments and findings |
| [`executive_summary.pdf`](executive_summary.pdf) | Executive summary and recommendations |
