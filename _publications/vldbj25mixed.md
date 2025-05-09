---
title: "Mixed Covers: Optimizing Updates and Queries Using Minimal Keys and Functional Dependencies (CCF-A)"
collection: publications
category: manuscripts
permalink: 
excerpt: ''
date: 2025-02-26
venue: 'VLDBJ'
paperurl: 'https://link.springer.com/article/10.1007/s00778-025-00910-2'
citation: '<strong>Zhuoxing Zhang</strong>, and Sebastian Link. "Mixed Covers: Optimizing Updates and Queries Using Minimal Keys and Functional Dependencies." The VLDB Journal 34, no. 3 (2025): 1-27.'
---

Covers for a set of functional dependencies (FDs) are fundamental for many areas of data management, such as integrity maintenance, query optimization, database design, and data cleaning. When declaring integrity constraints, keys enjoy native support in database systems while FDs need to be enforced by triggers or at application level. Consequently, maximizing the use of keys will provide the best support. We propose the new notion of mixed cover for a set of FDs, comprising the set of minimal keys together with a cover for the set of non-key FDs implied by the FD set. We establish sequential and parallel algorithms for computing mixed covers from a given set of FDs, and illustrate that they complement each other in terms of their performance. Even though FD covers are typically smaller in number or size than their corresponding mixed cover, the latter generate orders of magnitude lower overheads during integrity maintenance. We also quantify how mixed covers improve the performance of query, refresh and insert operations on the TPC-H benchmark under different constraint workloads and scaling factors. Finally, we illustrate the growth of performance improvement for optimal over minimal-reduced covers, justifying the significant time required for computing the former.
