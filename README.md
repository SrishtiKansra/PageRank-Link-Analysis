# PageRank Link Analysis [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SrishtiKansra/PageRank-Link-Analysis/blob/main/Project3_PageRank_Link_Analysis.ipynb)

Implementation of PageRank on an arXiv co-authorship network for Project 3 of Algorithms for Massive Data.

## 🚀 Project Overview
This project constructs a weighted co-authorship graph from the arXiv dataset and identifies influential authors using the PageRank algorithm.

The project includes:
- Custom PageRank implementation using power iteration
- Validation against NetworkX PageRank
- Spark MapReduce formulation of PageRank
- Scalability analysis
- Network visualisation and ranking analysis

## <img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/40424c2f-9ea4-4c91-8f75-7dd4cc8d6dae" /> Dataset
Source: arXiv metadata dataset (Cornell University)

Subset used:
- 50,000 papers
- ~85,000 authors
- ~500,000 collaboration edges

## <img width="25" height="25" alt="image" src="https://github.com/user-attachments/assets/424c0fc4-8606-4ef3-bc49-72717e69f9c3" /> Repository Structure
- `Project3_PageRank_Link_Analysis.ipynb` : Main notebook
- `Project3_Report.pdf` : Project report
- `README.md` : Repository description

## 🎯 Main Results
- Convergence achieved within 60 iterations
- Custom PageRank validated against NetworkX
- Spark implementation reproduces the same rankings
- Runtime scales approximately linearly with graph size

## 👩🏻‍💻 Author
Srishti Kansra  
MSc Data Science for Economics  
Università degli Studi di Milano
