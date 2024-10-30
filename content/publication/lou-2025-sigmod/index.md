---
title: "Towards a Converged Relational-Graph Optimization Framework"
date: 2024-10-30
publishDate: 2024-10-30T01:41:34.981585Z
authors: ["Yunkai Lou", "Longbin Lai", "Bingqing Lyu", "Yufan Yang", "Xiaoli Zhou", "Wenyuan Yu","Ying Zhang", "Jingren Zhou"]
publication_types: ["1"]
abstract: Interactive GPM (iGPM) is becoming increasingly important for data scientists to explore graphs in real life, where a series of graph pattern matching (GPM) queries are created and submitted in an interactive manner based on the insights provided by the prior queries. To solve the iGPM problem, three key considerations must be taken into account -- performance, usability and scalability -- namely if results can be returned in a timely manner, if queries can be written in a declarative way without the need of imperative fine-tune, and if it can work on large graphs. In this paper, we propose the GLogS system that allows users to interactively submit queries using a declarative language. The system will compile and automatically compute optimal execution plans for the queries, and execute them on an existing distributed dataflow engine. In the evaluation, we compare GLogS with the alternatives systems Neo4j and TigerGraph. GLogS outperforms Neo4j by $51\times$ on a single machine due to better execution plans. Additionally, GLogS can scale to handle large graphs with distributed capability. While compared to TigerGraph, GLogS is superior in usability, featuring an optimizer that can automatically compute optimal execution plans, eliminating the need of manual query tuning as required in TigerGraph.
featured: true
url_pdf: files/relgo-sigmod25.pdf
publication: "ACM SIGMOD/PODS International Conference on Management of Data 2025 (to appear)"
doi: "10.1145/3698828"
tags: ["Relational database", "Graph database", "Graph pattern matching", "Query optimization"]
---

