# SEABORN Visualizations - Pokemon Dataset
-

Visualizations of pokemon data using Seaborn.



## Getting Started

Uses anaconda to manage the environment.

### Requirements

You'll need the following installed to run the analysis successfully:

* Anaconda

### Installation

First create the anaconda environment:

```bash
conda env create -f environment.yml -n visualization
```

Activate the environment:

```bash
$ source activate visualization
```

Next, run the get the data.

```bash
./download_data
```

Start up Jupyter and visit localhost:8888 to see the analysis.

```bash
jupyter notebook
```

## Data Sources

Data source [https://elitedatascience.com/wp-content/uploads/2017/04/Pokemon.csv](https://elitedatascience.com/wp-content/uploads/2017/04/Pokemon.csv)


### Additional Info

To update project with new packages, add them to environment.yml, then type in

```bash
$ conda env update -f environment.yml -n isualization
```