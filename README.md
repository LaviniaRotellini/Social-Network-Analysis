# DO I WANT TO TALK TO YOU?

## Echo Chambers in the subreddit r/DebateVaccines

## Project Overview

This project investigates the interactions between Reddit users discussing one of the most controversial topics in online communities: vaccines.

The main objective is to understand whether echo chambers emerge within the subreddit r/DebateVaccines and to analyze how users with different attitudes towards vaccines interact with each other.

The study combines Social Network Analysis (SNA), Community Detection, Hypergraph Analysis, and Natural Language Processing (NLP) techniques to explore the structure and dynamics of online discussions.

## Objectives

The project is divided into four main analytical tasks:

### Network Characterization
Build and analyze a user interaction graph to investigate its structural properties, including degree distribution, connected components, clustering coefficient, density, and centrality measures.

### Static Community Detection
Identify communities within the network using four different algorithms:

Leiden

Label Propagation

Walktrap

DEMON

The detected communities are evaluated using internal and external evaluation metrics.

### Higher-Order Network Analysis
Model user interactions through hypergraphs, where users represent nodes and Reddit submissions represent hyperedges. This allows us to investigate how users participate in discussions across multiple posts.

### Sentiment Analysis and Echo Chamber Detection
Classify users according to their attitude towards vaccines (positive, negative, or neutral) using sentiment analysis techniques. Then, investigate whether users tend to interact with people sharing similar opinions and identify potential echo chambers.
