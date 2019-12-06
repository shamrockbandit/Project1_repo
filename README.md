# Project1_repo
contains all project 1 files for Scott, Eden, Meagan, and Jim

## Wrangling & Exploration Notebooks

* __readFreeData.ipynb__        - read Freedom Index Data, explore data, groupBy Coutnry, groupBy Region, means, %-change between 2008 and 2016
* __geoChart_hfscore.ipynb__        - Use Folium Package to chart heat map of mean human freedom (hf_score) by country on world map
* __geoChart_percChange_hfscore.ipynb__   - Use Folium package to chart heat map of %-change of mean hf_score by country on world map
* __bin_exploration.ipynb__              - explore binnng cut at mean of various scores
* __quartile_exploration.ipynb__          - explore quartile binning of personal freedom (pf_score)

## Hypothesis Analysis Notebooks
#### Personal Freedom vs. Econamic Freedom
* __pfscore and efscore.ipynb__  - analyze  Personal Freedom (PF) vs. Economic Freedom question
#### Human Freedom vs. Money Growth
* __money_growth.ipynb__    - analyze Human Freedom vs. Country Money Growth question
#### Human Freedom vs. Internet Expression 
* __pf_internet score vs hf_score.ipynb__   - analyze Human Freedom (PF) vs. Freedom of Internet Expression question
#### Personal Freedom vs. Perception of Business Corruption
* __corruption_freedom.ippynb__  - initial analysis of Personal Freedom (PF) vs. Perception of Business Corruption
* __quartile_exploration.ipynb__ - final analysis of Personal Freedom (PF) vs. Preception of Business Corruption by top and bottom quartile bin of PF

## Plots (~/plots)
### Exploration Plots
* freedomplot_hfscore.html  - World heat map of 2016 Human Freedom (hf_score)
* freedomplot_percChange_hfscore.html - World heat map of %-change of Human freedom between 2008 and 2016
* hi-lo_bin_plot.png  - Scatter olot with hi-lo lines indicating bins cut across mean of perception of business corruption

### Hypotheses Analysis plots
#### Personal Freedom vs. Econamic Freedom
* PFScorevEFScoreRegress.png
* pf_quartiles_v_efscores.png
#### Human Freedom vs. Money Growth
* MoneyGrowthvHFscore.png
#### Human Freedom vs. Internet Expression 
* internet.png
#### Personal Freedom vs. Perception of Business Corruption
* top_quartile.png
* bottom_quartile.png
