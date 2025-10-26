# Historical Social Network Analysis

## Overview
This project analyzes a correspondence network from the Tudor State Papers, modeling relationships among historical figures based on letters exchanged between them.  
The analysis explores triadic closure, degree distributions, and centrality using graph-theoretic methods.

## Objectives
- Represent historical communication as a directed and undirected network.
- Compute degree, clustering coefficient, and eigenvector centrality for each node.
- Test for triadic closure using a configuration-model-based null hypothesis.
- Interpret network structure in the context of historical relationships.

## Methods & Tools
**Tools:** Python, NetworkX, pandas, matplotlib, numpy  
**Techniques:**
- Directed and undirected graph modeling  
- Configuration model for null hypothesis testing  
- Degree and centrality analysis  
- Clustering and visualization of network structure  

## Key Findings
- The network exhibited significant triadic closure, with an observed clustering coefficient (~0.17) far exceeding values under the null model (~0.05).  
- Thomas Cromwell and Henry VIII emerged as central, influential nodes with low clustering coefficients, suggesting they served as gatekeepers connecting otherwise unlinked individuals.  
- Figures like Katharine of Aragon and Desiderius Erasmus occupied smaller, tightly connected communities.  

## Skills Demonstrated
- Network analysis with NetworkX  
- Hypothesis testing using null models  
- Data visualization and interpretation  
- Graph metrics (degree, clustering, centrality)  
- Communicating statistical insights in context
