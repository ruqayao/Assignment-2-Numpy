# Assignment-2-Numpy

# Purpose
This project is meant to demonstrate how to load tabular sports data into NumPy ndarrays and perform data manipulation using a simple class-based design.
Using NBA player statistics, the program calculates shooting accuracy, scoring efficiency, and defensive averages for each player in each season,
then identifies the top 100 player-seasons for each metric.

# Class Overview
All logic is grouped into a single class, NBAStats - Handles data loading, metric calculations, and ranking output.

# Attributes
- self.text – NumPy ndarray containing string data (player names, seasons)
- self.num – NumPy ndarray containing numeric statistics
- self.results – Combined ndarray containing player, season, and computed metrics

# Methods
- __init__() – Loads the dataset into NumPy arrays
- safe_divide() – Performs division while safely handling division by zero
- calculate_metrics() – Computes all required statistics
- top_100() – Displays the top 100 player-seasons for a selected metric

# Limitations
- No minimum games played filter
- Missing values are treated as zero
- Results are printed to the console only
- Uses season totals rather than per-game logs
