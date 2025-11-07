# Victim Crime Perception

This project analyzes and clusters individuals based on their perceived experiences of victimization using survey data.

## Project Overview
The goal is to explore patterns in how victim perceive crime and tend to report to authorities/parents/else, and to group respondents into meaningful clusters by their perception profiles.

## Key Steps
- Importing and cleaning survey data (from 2016 & 2019 United States) using `pandas` and `pyreadstat`
- Selection of Features and merging of datasets
- Handling the NaN values
- Exploratory Data Analysis (EDA) with `matplotlib` and `seaborn`  
- Clustering the dataset with K-Means clustering with initialization of clusters with K-Means++ algorithm
- Finding the suitable number of clusters using metrics Silhouette and Inertia
- Selection of suitable number of clusters
- Visualization of cluster outcomes and interpretation of patterns
- Interpretation of the cluster and the group of people in clusters and identifying the perception of the group of Victims in that category  

## 📁 Repository Structure
Victim‐Crime-Perception/
│
├── VictimCrimePerception.ipynb # Main analysis notebook
├── Victim-Crime-Perception/ # Supporting directory (data, scripts, etc.)
├── requirements.txt # Project dependencies
└── README.md # This file

## ⚙️ Installation
```bash
git clone https://github.com/vbek/Victim‐Crime-Perception.git
cd Victim‐Crime‐Perception
pip install -r requirements.txt

jupyter notebook VictimCrimePerception.ipynb
