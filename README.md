# Data Mining with Graph Neural Networks – NFL Player Interaction Analysis

This repository contains a **data mining project applying Graph Neural Networks (GNNs)** to player tracking data from the **NFL Big Data Bowl**. The goal is to model the **relational structure of players on the field** using graphs, then train GNN models to extract insights and perform predictive analysis on football plays.

---

## Motivation

American football is inherently relational: each play defines how players move relative to one another, and the interactions between players often determine key outcomes such as pass direction or play success.

Traditional models (e.g., MLPs or feature-based classifiers) treat plays as unordered sets of features, ignoring spatial and relational information. **Graph Neural Networks** improve this by representing each play as a **graph** where:

- **Nodes** = individual players  
- **Edges** = relationships (e.g., proximity or positional similarity)  
- **Node features** = tracking data, movement vectors, orientation

This graph-based modeling captures **spatial and interaction patterns** that conventional methods miss, leading to richer representations and improved predictive performance. 

---

##  Repository Contents

  ├── data/<br>
  │    ├── games.csv<br>
  │    ├── ...<br>
  │    └── players.csv<br>
  └── NFL Data Mining w GNN.ipynb<br>
