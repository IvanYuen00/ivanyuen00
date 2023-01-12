# Introduction

In the era of advanced technology, information updates every second on the internet,
and social networks are evolving continuously and constantly. The classical
paradigm that reads static datasets is inadequate for the current social network and
web graph setting. The accuracy is decreasing due to the high information
transmission rate nowadays.
To address the PageRank accuracy declining problem, the research paper
“PageRank on an Evolving Graph” by Bahmani, Bahman, et al. proposed it is
necessary to design an algorithm that crawls the pages with its decision and
computes the PageRank using the obtained information with a lower error. The
public is pursuing the internet to understand their needs and be more convenient for
receiving information, entertaining, and communicating. Improving the evolving
graph is always needed due to social networks and web graphs changing
continuously.

# Target
Reproduce the research paper “PageRank on an Evolving Graph” by Bahmani, Bahman, et al.. Provide implementation on the datasets used in the paper and test the performance of the proposed algorithms.

# Methodologies
The solution of the research paper to compute the PageRank with as little error as
possible was implemented in the following steps:
First, set up 2 baseline probing, Random probing and Round Robin probing; these
are the traditional probing with an outstanding performance previously in a fixed
dataset. Furthermore, set up another 2 improved test probing, Proportional Probing
and Priority probing. Second, compare the test probing to the baselines using 3
different datasets. Observe and understand the performance of the above algorithms
to choose the algorithm with the lowest error in PageRank computation.

# Theoretical Prove
In this report, we hold the assumption:
Number of nodes is fixed at n
Number of edges remain unchanged at m
Rate of probe = Rate of change
The results shows that the evaluation of the expected pagerank value is given as:
The bounding represents that the expected PageRank values of each algorithm are
bounded by the true PageRank values, which is expected.

$$(1-O(1/m))\varphi ^t\leq E[π|G^{t-1},H^t]\le (1+O(1/m))\varphi ^t$$


# Results and Conclusion
The detail of the prove and results are given in the full report.
[SDSC3001 Written Report.pdf](https://github.com/IvanYuen00/SDSC3001-Course-Project-PageRank-on-an-evolving-graph/files/10400309/SDSC3001.Written.Report.pdf)
