# Sports Analytics Project

This repository contains a collection of Jupyter Notebooks for data collection, clustering, player analysis, and team analysis in sports analytics. The notebooks leverage various data sources and provide insights through clustering techniques and detailed analysis.

Please see "Top5LeaguesAnalysisProject_Writeup.pdf" for a concise overview of the project.

## Repository Structure

- `datacollection.ipynb`: Notebook for collecting and preprocessing the data from various sports sources.
- `clustering.ipynb`: Notebook for performing clustering analysis on the collected data.
- `clustering2.ipynb`: An additional clustering notebook to explore different clustering methods or parameters.
- `player_analysis.ipynb`: Notebook focused on the analysis of individual player performance and metrics.
- `team_analysis.ipynb`: Notebook dedicated to the analysis of team performance and metrics.

## Notebooks Description

### 1. Data Collection (`datacollection.ipynb`)

This notebook includes scripts to:
- Collect data from multiple sports data sources.
- Preprocess the data to ensure consistency and usability.
- Save the cleaned data for further analysis.

### 2. Clustering Analysis (`clustering.ipynb`)

This notebook performs clustering analysis on the sports data:
- Implements various clustering algorithms such as K-Means, DBSCAN, etc.
- Visualizes the clustering results using scatter plots and other appropriate visualizations.
- Analyzes the characteristics of each cluster.

### 3. Clustering Analysis 2 (`clustering2.ipynb`)

This notebook explores additional clustering techniques:
- Tests different clustering algorithms and parameters.
- Provides comparative visualizations to highlight differences in clustering outcomes.
- Offers insights into the best clustering methods for the dataset.

### 4. Player Analysis (`player_analysis.ipynb`)

This notebook focuses on individual player metrics:
- Analyzes player performance using statistical methods.
- Visualizes player performance metrics through various plots such as bar charts, line graphs, etc.
- Provides comparative analysis between players.

### 5. Team Analysis (`team_analysis.ipynb`)

This notebook analyzes team performance:
- Investigates team metrics and overall performance.
- Visualizes team performance using appropriate plots.
- Compares different teams based on various metrics.

## Data and Plots

The notebooks include various plots to visualize the data and analysis results:
- Scatter plots for clustering results.
- Bar charts and line graphs for player and team performance metrics.
- Comparative plots to highlight differences and insights.

## Requirements

To run these notebooks, you need the following Python packages:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `jupyter`

Install the required packages using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Usage

1. Clone the repository: ```bash git clone https://github.com/yourusername/sports-analytics.git ```
2. Navigate to the repository directory: ```bash cd sports-analytics ```
3. Start Jupyter Notebook: ```bash jupyter notebook ```
4. Open and run the desired notebook.

## Contributing
Contributions, issues, and feature requests are welcome. Feel free to check [issues page](https://github.com/yourusername/coot-sorter/issues) if you want to contribute.

## Author
Matt Gurgiolo

## License
This project is open source and available under the [MIT License](LICENSE.txt).
