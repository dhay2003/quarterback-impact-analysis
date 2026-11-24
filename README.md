# NFL Quarterback Efficiency & Team Success Analysis (2021-2026)

## Overview
This project analyzes the relationship between quaterback efficiency, pass protection, and team success between the 2021 - 2026 NFL seasons.

Using six seasons of NFL player statistics, team statistics, and game results, the project investigates which quarterback performance metrics are most strongly associated with winning. The analysis combines quarterback-level performance data with team-level context to evaluate how factors such as efficiency, turnovers, and pass protection contribute to successful outcomes. 

## Research Questions
### 1 - Which quarterback metrics are most strongly associated with winning?

The project evaluates  both traditional and advanced performance metrics, including: 
- EPA per Game ( Expected Points Added
- Completion Percentage
- Touchdown-to-Intercetption Ratio
- Yards per Attempt
### 2 - How Important is pass protection?

Quarterback performance is heavily influenced by offensive line play. This project explores whether teams allowing fewer sacks are more likely to win. 

### 3 - Do efficiency metrics explain success better than traditional passing statistics?

The analysis compares advanced efficiency measures against more traditional volume-based statistics to determine which metrics better explain team outcomes. 

## Data Sources

### NFLverse

The project utilizes publicly available NFLverse datasets from the 2021 - 2026 NFL regular season

## Methodology

### Data Intergration

The project combines:

1. Quarterback season statistics
2. Team season statistics
3. Team records generated from schedule and game-result data

### Feature Engineering

Additional metrics were created, including:

- EPA per Game
- Completion Percentage
- Yards per Attempt
- Touchdown-to-Interception Ratio
- Winning Percentage
- Point Differential

### Qualification Criteria

To reduce the impact of small sample sizes:

- Quarterbacks were filtered to a mninum threshold of games played when comparing season level performance
- Efficiency metrics were normalized on a per-game basis.

## Dashboard

### Quarterback Efficiency & Team Success

The Tableau dashboard highlights: 
- EPA/game vs Winning Percentage
- Pass Protection vs Winning Percentage
- Top 15 Quarterback seasons by EPA/Game

### Dashboard Preview

Tableau Public: 
https://public.tableau.com:9443/views/NFLQuarterbackEfficiencyTeamSuccess2021-2026/NFLQuarterbackEfficencyTeamSuccess2021-2026?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Key Findings

### EPA per game was the strongest quarterback metric
EPA per game demonstrated the strongest relationship with team success among quarterback metrics analyzed. Pass protection also played a key role with less team sacks leading generally to greater team success.

## Technologies Used

### Programming
- Python
- Pandas
- Numpy
### Data Visualization

- Tableau Public
- Matplotlib
- Seaborn

### Development Tools
- Git
- Github
- Jupyter Notebook

## Author
Dylan Hayward
UH CIS Grad |Data Analytics|Tableau|AWS



