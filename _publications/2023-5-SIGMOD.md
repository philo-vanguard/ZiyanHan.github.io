---
title: "**Discovering Top-k Rules using Subjective and Objective Criteria"
collection: publications
permalink: /publication/2023-5-SIGMOD
date: May, 2023
venue: 'Proceedings of the ACM on Management of Data (SIGMOD)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3588924'
citation: 'Fan, Wenfei, Ziyan Han, Yaoshu Wang, and Min Xie. "Discovering Top-k Rules using Subjective and Objective Criteria." Proceedings of the ACM on Management of Data 1, no. 1 (2023): 1-29.'
---

### Abstract

This paper studies two questions about rule discovery. Can we characterize the usefulness of rules using quantitative criteria? How can we discover rules using those criteria? As a testbed, we consider entity enhancing rules (REEs), which subsume common association rules and data quality rules as special cases. We characterize REEs using a bi-criteria model, with both objective measures such as support and confidence, and subjective measures for the user's needs; we learn the subjective measure and the weight vectors via active learning. Based on the bi-criteria model, we develop a top-k algorithm to discover top-ranked REEs, and an any-time algorithm for successive discovery via lazy evaluation. We parallelize these algorithms such that they guarantee to reduce runtime when more processors are used. Using real-life and synthetic datasets, we show that the algorithms are able to find top-ranked rules and speed up conventional rule-discovery methods by 134X on average.
