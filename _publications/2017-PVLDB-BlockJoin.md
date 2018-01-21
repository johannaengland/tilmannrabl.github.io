---
layout: publication
title: "BlockJoin: Efficient Matrix Partitioning Through Joins"
author: "Andreas Kunft, Asterios Katsifodimos, Sebastian Schelter, Tilmann Rabl, Volker Markl"
booktitle: "Proceedings of the VLDB Endowment"
volume: 10
number: 13
pages: "2061-2072"
year: "2017"

abstract: "Linear algebra operations are at the core of many Machine
Learning (ML) programs. At the same time, a considerable amount of the effort 
for solving data analytics problems is spent in data preparation. As a result, end-to-end 
ML pipelines often consist of (i) relational operators used for joining the input data, 
(ii) user defined functions used for feature extraction and vectorization, and (iii) linear 
algebra operators used for model training and cross-validation. Often, these pipelines need to scale out to large
datasets. In this case, these pipelines are usually implemented on top of dataflow engines like Hadoop, Spark, or Flink. 
These dataflow engines implement relational operators on 
row-partitioned datasets. However, efficient linear algebra operators use block-partitioned matrices. As a 
result, pipelines combining both kinds of operators require rather expensive changes to the physical representation, in
particular re-partitioning steps. In this paper, we investigate the potential of reducing shuffing costs by fusing relational
and linear algebra operations into specialized physical operators. We present BlockJoin, a distributed join algorithm
which directly produces block-partitioned results. To minimize shuffing costs, BlockJoin applies database techniques
known from columnar processing, such as index-joins and late materialization, in the context of parallel dataflow 
engines. Our experimental evaluation shows speedups up to 6x and the skew resistance of BlockJoin compared to 
state-of-the-art pipelines implemented in Spark."
---

