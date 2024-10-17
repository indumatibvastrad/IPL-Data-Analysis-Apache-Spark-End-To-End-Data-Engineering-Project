## Project Overview

This project analyzes cricket match data using Apache Spark to provide insights into team performances, 
player statistics, and the impact of match conditions. The analysis includes various transformations and 
visualizations to facilitate understanding of match outcomes and player contributions.

### Transformations Applied

1. **Aggregation**: Calculated total and average runs scored in each match and inning.
2. **Window Function**: Calculated the running total of runs in each match for each over.
3. **Conditional Column**: Flagged high impact balls (wickets or runs over 6, including extras).
4. **High Margin Win Categorization**: Categorized wins into high, medium, and low margins.
5. **Toss Impact Analysis**: Analyzed the correlation between toss winners and match outcomes.
6. **Player Categorization**: Grouped players based on batting hand for trend analysis.
7. **Veteran Status Column**: Added a column to indicate veteran status based on player age.
8. **Dynamic Debut Years Calculation**: Calculated years since debut for player experience assessment.

### Visualizations Created

- Top scoring batsmen per season.
- Toss impact on individual matches.
- Distribution of scores by venue.
- Most frequent dismissal types.
- Team performance after winning toss.

This project showcases the robust capabilities of Apache Spark for processing large datasets and 
deriving meaningful insights through efficient transformations and visualizations.
