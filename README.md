# Code and data for MGGG's December 2018 workshop

This repo contains:

- `Template.py`: A template python script for using [GerryChain](https://github.com/mggg/gerrychain) to generate ensembles of districting plans.
- `Template.ipynb`: The same template as a Jupyter notebook.
- `/graphs/`: Pre-made adjacency graphs of Alaska, Massachusetts, Missouri, Pennsylvania, and Wisconsin for use with GerryChain.
  The `rook` folder contains graphs made using Rook adjacency, and the `queen` folder contains graphs made using Queen adjacency.
  The repos for the source shapefiles are in [mggg-states](https://github.com/mggg-states), and contain information on all
  of the data (population counts, vote totals, Census GEOIDs, etc.) stored on the graphs. You'll need this information to
  configure GerryChain runs using the graphs.
