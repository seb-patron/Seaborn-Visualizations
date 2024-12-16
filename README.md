# Seaborn Visualizations - Pokémon Dataset

## Overview
This project demonstrates data visualization techniques using Seaborn and the Pokémon dataset. It explores various visualization methods to analyze Pokémon statistics and characteristics, making complex data relationships easier to understand through visual representations.

## Features
- **Scatterplots**: Compare Attack vs. Defense stats with color-coded evolution stages
- **Boxplots**: Analyze the distribution of various Pokémon statistics
- **Violin Plots**: Visualize stat distributions across different Pokémon types
- **Heatmaps**: Explore correlations between different attributes
- **And more**: Additional visualization techniques for comprehensive data analysis

## Getting Started

### Prerequisites
This project uses Anaconda to manage the Python environment. Make sure you have the following installed:
- Anaconda (or Miniconda)

### Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/seaborn-pokemon.git
cd seaborn-pokemon
```

2. Create and activate the Anaconda environment:
```bash
conda env create -f environment.yml -n visualization
conda activate visualization
```

3. Download the dataset:
```bash
./download_data
```

4. Launch Jupyter Notebook:
```bash
jupyter notebook
```

5. Navigate to the `notebooks` directory and open the visualization notebook to explore the analysis.

## Data Source
The dataset used in this project contains information about Pokémon including their types, stats, and evolutionary stages.

Data source: [Pokémon Dataset](https://elitedatascience.com/wp-content/uploads/2017/04/Pokemon.csv)

## Project Structure
```
.
├── data/                # Data files (will be downloaded)
│   └── raw/             # Raw data files
├── img/                 # Generated visualization images
├── notebooks/          # Jupyter notebooks with analysis and visualizations
├── download_data       # Script to download the data
├── environment.yml     # Conda environment specification
└── README.md           # Project documentation
```

## Additional Information
To update the project with new packages, add them to environment.yml, then update the environment:

```bash
conda env update -f environment.yml -n visualization
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.