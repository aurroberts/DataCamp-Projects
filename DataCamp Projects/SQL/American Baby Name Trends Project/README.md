## Project Overview
This project analyzes U.S. baby name date from 1920 to 2020 using SQL. The goal was to explore how naming trends have changed across generations - identifying timeless classics vs. short-term fads and ranking popularity over time.

## Tools Used
- PostgreSQL/SQL
- Window Functions (RANK)
- CASE WHEN logic
- Filtering, Grouping, Aggregation
- Set operations (INTERSECT)

## Key Insights
- Classified names as "Classic" iff they appeared in 50 or more years, and "Trendy" if not.
- Ranked top 20 male names and evaluated the popularity of names like Paul.
- Identified which female names appeared in both 1920 and 2020, using 'INTERSECT'.

## Files
1. 'notebook.ipynb': Contains all SQL queries and commentary
2. 'baby_names.jpg': Visual preview for project banner

## How to Run
- Open the notebook in Jupyter or view on GitHub.
