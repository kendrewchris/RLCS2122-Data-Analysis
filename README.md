# RLCS2122-Data-Analysis
> Authors: [David Ryan](https://github.com/davidry777), [Kendrew Christanto](https://github.com/kendrewchris), [Jonathan Thai](https://github.com/jonathanht), [Nicholas Chang](https://github.com/nickthechang)

## Project Description
> Python data analysis project for finding correlations between winning matches alongside various game statistics of players that perform in the Rocket League Championship Series 2021-2022.
> 
> We hope to accomplish by relating winning matches to data points such as number of goals scored, car boost amount, movement, positioning, and game controls with respect to wins. 
> The languages/tools/technologies we plan to use are:
>   * [Python](https://www.python.org) - A high-level, interpreted, general-purpose programming language.
>   * [NumPy](https://numpy.org) - A library for adding support for large, multi-dimensional arrays and matrices.
>   * [Pandas](https://pandas.pydata.org) - A library for data manipulation and analysis. Useful for manipulating our dataset.
>   * [Matplotlib](https://matplotlib.org) - Comprehensive library for creating static, animated, and interactive visualizations in Python.
>   * [Seaborn](https://seaborn.pydata.org) - Data viz library for easily creating statistical graphs. Built on top of Matplotlib.
>   * [Scikit-learn](https://scikit-learn.org/stable/) - Machine learning library for features various classification, regression and clustering algorithms. We'll be using this library for doing regression analysis, k-means clustering, and k-nearest neighbors.
>   * [Google Colab](https://colab.research.google.com/?utm_source=scs-index) - A [Jupyter Notebook](https://jupyter.org) interface created by Google Research that allows us to write and execute Python code. Great for easily sharing code.

## Dataset
> The dataset we have is a *Rocket League Championship Series* dataset that includes game data for 34,000 teams and 101,000 players. The team dataset includes a team's number of goals, assists, saves, and assists, along with a team's boost amount collected, total distance of movement, amount of time spent on offensive and defensive positioning, and the number of cars demolished.
> 
> The player dataset contains the same features as the team dataset, with differences only in the amount of goal participation and whether the winning player is an mvp or not.
> 
> **Our Dataset:** https://www.kaggle.com/datasets/dylanmonfret/rlcs-202122
> 
> Because there's so much data, we'll look into specifically `games_by_players.csv` and `games_by_teams.csv`. The data will be cleaned to only include relevant data points of interest
