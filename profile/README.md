# Project: Graph-Based Anomaly Detection in Healthcare Data
>MathSys 2021-22 MSc group project at University of Warwick.

Our external partners at [Kirontech](https://www.kirontech.com/) offer a Health Insurance Platform that helps insurance payers deal with anomalies in their insurance claims. Healthcare data naturally involves a number of relevant interactions between different entities. Kirontech has yet to explore graph-based anomaly detection (GBAD) techniques.

**The goal of this project is to adopt different GBAD methods on Kirontech's real-life dataset and provide evidence that graph-based data is useful to examine different anomalies.**

<br/>

## Main References
### Literature Review
- [Fraud detection: A systematic literature review of graph-based anomaly detection approaches](https://www.sciencedirect.com/science/article/pii/S0167923620300580) - Tahereh Pourhabibi et al (2020)

### Research Methodology
- **CADA**: [A Community-Aware Approach for Identifying Node Anomalies in Complex Networks](https://link.springer.com/chapter/10.1007/978-3-030-05411-3_20) - TJ Helling, JC Scholtes, FW Takes (2018)
- **Community Detection - Spectral Bipartitioning & Modularity Maximization**: [Finding community structure in networks using the eigenvectors of matrices](https://arxiv.org/abs/physics/0605087) - M. E. J. Newman (2006)
  - **Modularity Maximization - Leiden Algorithm**:
    - [From louvain to leiden: guaranteeing well-connected communities](https://www.nature.com/articles/s41598-019-41695-z) - TV A, W L, van Eck N J (2019)
    - [Narrow scope for resolution-limit-free community detection](https://arxiv.org/pdf/1104.3083.pdf) - VA Traag, PV Dooren, Y Nesterov (2011)
  - **Modularity Maximization - Robustness**: [Dynamic communities in multichannel data: An application to the foreign exchange market during the 2007-2008 credit crisis](https://ui.adsabs.harvard.edu/abs/2009Chaos..19c3119F/abstract) - DJ Fenn, et al (2009)
- **PSS Algorithm**: [Detecting Healthcare Fraud through Patient Sharing Schemes](https://link.springer.com/chapter/10.1007/978-3-642-29166-1_39) - Aryya Gangopadhyay, Song Chen, and Yelena Yesha (2012)
- **OddBall**: [OddBall: Spotting Anomalies in Weighted Graphs](http://www.cs.cmu.edu/~mmcgloho/pubs/pakdd10.pdf) - Leman Akoglu, Mary McGlohon, Christos Faloutsos (2010)
<br/>

## Python Packages for Method Implementation
We use Python for programming in this project.
- Network Analysis - **NetworkX**: https://networkx.org/documentation/stable/reference/index.html
- Anomaly Detection - **cada**: https://github.com/thomashelling/cada
- Modularity Maximization via Leiden Algorithm - **CDlib**: https://cdlib.readthedocs.io/en/latest/index.html
<br/>

## Network Visualization
See resources [here](https://github.com/YuetingH).

<br/>


## Other Techniques
- Network Database - **Neo4j**: https://neo4j.com/developer/get-started/
