# gaia-open-cluster-dbscan
Finding an Open Cluster in Proper Motion Space Using Gaia Data Release 3
# Identifying an Open Cluster in Gaia DR3

This repository contains the code used to identify and validate a co-moving open star cluster using Gaia DR3 data from the European Space Agency.

## Project Overview
We query Gaia DR3 using Astroquery and apply the DBSCAN clustering algorithm in proper motion space (pmRA, pmDEC), with parallax used as a validation metric. Candidate clusters are validated using:
- Proper motion scatter plots
- k-distance (epsilon selection) plots
- Parallax distributions
- Color–Magnitude Diagrams (CMDs)
- Sky maps
- Proper motion vector fields

## Data Source
- Gaia Data Release 3 (ESA Gaia Archive)

## Methods
- ADQL queries via Astroquery
- Data preprocessing using RUWE and visibility period filters
- Feature standardization
- DBSCAN clustering
- Astrophysical validation using CMDs and parallaxes

## Repository Contents
- `gaia_cluster_analysis.ipynb`: Main analysis notebook
- `plots/`: Validation figures used in the report

## Authors
- Danielle Byrd
- Isabella Adame
- Zehra Naqvi
- Luke Reyes
- Catherine Kim
