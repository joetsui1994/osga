# Optimal Disease Surveillance with Graph-Based Active Learning

​​Joseph L.-H. Tsui<sup>§</sup>, Mengyan Zhang<sup>§</sup>, Prathyush Sambaturu, Simon Busch-Moreno, Oliver G. Pybus, Seth Flaxman<sup>#</sup>, Elizaveta Semenova<sup>#</sup>, Moritz U. G. Kraemer<sup>#</sup>

**<sup>§</sup>** Contributed equally to this work<br/>
**<sup>#</sup>** Contributed equally to this work

---

This repository contains data and scripts used to generate results
presented in our submission to [epiDAMIK 2024](https://epidamik.github.io/dates.html). Please note that some scripts may need small adjustments to run depending on local setup.

## Abstract

_The detection and tracking of the spread of emerging pathogens is critical to the design of effective public health responses. Policymakers face the challenge of allocating finite testing resources across locations, with the goal of maximising the information obtained about the underlying disease distribution. We model this decision-making process as an iterative node classification problem on an undirected and unweighted graph, in which nodes represent locations and edges represent movement of infectious agents among them. To begin, a number of nodes are selected for testing and determined to be either infected or uninfected. Test feedback is then used to update estimates of the probability of unobserved nodes being infected and to inform the selection of nodes for further testing at the next iteration, until a certain resource budget is exhausted. Under this framework, we evaluate and compare the performance of previously developed active learning policies, including node-entropy and Bayesian Active Learning by Disagreement. Using data from simulated outbreaks on both random and empirical human mobility networks, we explore the performances of these policies under different outbreak scenarios and graph structures. Further, we propose a novel policy that considers the distance-weighted average entropy of infection predictions among the unobserved neighbours of each candidate node. Our proposed policy outperforms existing ones in most outbreak scenarios, leading to reduction in the number of tests required to achieve a certain predictive accuracy. Our findings could help design cost-effective surveillance policy for emerging and endemic pathogens, accelerating disease detection in resource-constrained situations._