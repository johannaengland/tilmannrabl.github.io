---
title: "Query Centric Partitioning and Allocation for Partially Replicated Database Systems"
author: "Tilmann Rabl, Hans-Arno Jacobsen"
booktitle: "Proceedings of the 2017 ACM International Conference on Management of Data"
pages: "315-330"
year: "2017"

abstract: "A key feature of database systems is to provide transparent access to stored data. 
In distributed database systems, this includes data allocation and fragmentation. Transparent 
access introduces data dependencies and increases system complexity and inter-process communication. 
Therefore, many developers are exchanging transparency for better scalability using sharding and 
similar techniques. However, explicitly managing data distribution and data flow requires a deep 
understanding of the distributed system and the data access, and it reduces the possibilities for optimizations.

To address this problem, we present an approach for efficient data allocation that features good 
scalability while keeping the data distribution transparent. We propose a workload-aware, 
query-centric, heterogeneity-aware analytical model. We formalize our approach and present an 
efficient allocation algorithm. The algorithm optimizes the partitioning and data layout for 
local query execution and balances the workload on homogeneous and heterogeneous systems according 
to the query history. In the evaluation, we demonstrate that our approach scales well in performance 
for OLTP- and OLAP-style workloads and reduces storage requirements significantly over replicated 
systems while guaranteeing configurable availability."
---

