# NBA Trends Project

This project analyzes National Basketball Association (NBA) data to explore associations between teams, win-rates, playoff appearances, and more. The analysis is performed using Python, pandas, numpy, matplotlib, seaborn, and scipy.

## Data Source

- The data is sourced from FiveThirtyEight's [Complete History Of The NBA](http://fivethirtyeight.com/interactives/the-complete-history-of-every-nba-team-by-elo) and [Basketball Reference](http://www.basketball-reference.com/).
- The dataset includes 5 teams and 10 columns, plus a constructed column `point_diff` (the difference between `pts` and `opp_pts`).

## Project Tasks

In this project, you’ll analyze data from the NBA (National Basketball Association) and explore possible associations.

This data was originally sourced from 538’s Analysis of the Complete History Of The NBA and contains the original, unmodified data from Basketball Reference as well as several additional variables 538 added to perform their own analysis.

You can read more about the data and how it’s being used by 538 here. For this project we’ve limited the data to just 5 teams and 10 columns (plus one constructed column, point_diff, the difference between pts and opp_pts).

You will create several charts and tables in this project, so you’ll need to use plt.clf() between plots in your code so that the plots don’t layer on top of one another.

Let’s get started!

## How to Run

1. Ensure you have Python 3.x installed.
2. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```
3. Open `NBA_Trends_Project.ipynb` in Jupyter Notebook or VS Code.
4. Run the cells to reproduce the analysis and visualizations.

## Files

- `nba_games.csv`: NBA game data for analysis.
- `NBA_Trends_Project.ipynb`: Jupyter notebook with all analysis steps and code.

## References

- [FiveThirtyEight NBA Elo Data](https://github.com/fivethirtyeight/data/tree/master/nba-elo)
- [Codecademy NBA Trends Project](https://www.codecademy.com/projects/practice/nba-trends)

---

_This project is for educational purposes and is based on open datasets._
