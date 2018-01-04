---
layout: publication
title: "Distributed Machine Learning - but at what COST?"
author: "Christoph Boden, Tilmann Rabl, Volker Markl"
booktitle: "NIPS Workshop on ML Systems"
pages: ""
year: "2017"

abstract: "Training machine learning models at scale is a popular workload for distributed
data flow systems. However, as these systems were originally built to fulfill quite
different requirements it remains an open question how effectively they actually
perform for ML workloads. In this paper we argue that benchmarking of large scale
ML systems should consider state of the art, single machine libraries as baselines
and sketch such a benchmark for distributed data flow systems.

We present an experimental evaluation of a representative problem for XGBoost,
LightGBM and Vowpal Wabbit and compare them to Apache Spark MLlib with
respect to both: runtime and prediction quality. Our results indicate that while being
able to robustly scale with increasing data set size, current generation data flow
systems are surprisingly inefficient at training machine learning models at need
substantial resources to come within reach of the performance of single machine
libraries."
---

