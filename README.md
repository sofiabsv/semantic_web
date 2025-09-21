# Spotify Semantic Dataset

## Overview

**Spotify Semantic Dataset** is a student project exploring semantic data modelling and linking using RDF/Turtle formats and interactive notebooks. The main example is a music-domain dataset derived from Spotify, enriched with semantic relationships and visualisations.

This project was developed as the **final project for the Semantic Web module at HTWK Leipzig**.

## Dataset

We used the **[Most Streamed Spotify Songs 2024](https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024)** dataset from Kaggle as the foundation for our analysis and semantic modelling.

## Project Structure

| File / Folder           | Description                                                                |
| ----------------------- | -------------------------------------------------------------------------- |
| `spotify.ttl`           | RDF/Turtle file: extended Spotify dataset with semantic statements.        |
| `spotify_project.csv`   | Raw tabular data from Kaggle (tracks, artists, features).                  |
| `spotify_project.ipynb` | Jupyter notebook: processing, analysis, graph creation, and visualization. |
| `out.json`              | Exported JSON data from transformations/queries.                           |
| `visuals/`              | Folder with generated visual artifacts (charts, graphs, etc.).             |

## Features

* Transform tabular music data into semantic triples.
* Use RDF/Turtle to model relationships (artist → album, track → features).
* Visualize graph structures and query outputs.
* Modular steps to extend or reuse for other datasets.

## Getting Started

1. Ensure Python 3.x is installed (recommended: use a virtual environment).
2. Install required libraries:

   ```bash
   pip install rdflib pandas matplotlib networkx jupyter
   ```
3. Open and run `spotify_project.ipynb` in Jupyter Notebook.
4. Explore the semantic model in `spotify.ttl` and experiment with queries.

## Goals

* Practice applying semantic web technologies (RDF, Turtle, SPARQL).
* Learn how to transform real-world data into linked data formats.
* Explore graph-based visualisation of music data.

## Authors

* Sofia Berdichevska
* Franca Lenz

## License

This project is for educational purposes as part of academic coursework at HTWK Leipzig. Contributions and improvements are welcome.

