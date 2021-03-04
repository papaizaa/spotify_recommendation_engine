# Spotify Recommender System

In this project, the goal is to create the worst music recommendation engine. My goal was to see if I could use my own listening habits to generate a playlist of music that I would not like. So I used my own spotify listening history and a content based filtering approach to create this recommendation engine


## Setup
```
conda create -y --name recommendor python=3.7
conda install --force-reinstall -y -q --name py37 -c conda-forge --file requirements.txt
conda activate recommendor

...
jupyter notebook
<muck around in jupyter>
conda deactivate
```
