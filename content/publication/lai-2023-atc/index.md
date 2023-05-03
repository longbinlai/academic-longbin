---
title: "GLogS: Interactive Graph Pattern Matching Query At Large Scale"
date: 2023-05-03
publishDate: 2023-05-03T01:41:34.981585Z
authors: ["Longbin Lai", "Yufan Yang", "Zhibin Wang", "Yuxuan Liu", "Haotian Ma", "Sijie Shen", "Bingqing Lyu", "Xiaoli Zhou", "Wenyuan Yu", "Zhengping Qian", "Chen Tian", "Shen Zhong", "Yeh-Ching Chung", "Jingren Zhou"]
publication_types: ["1"]
abstract: Interactive GPM (iGPM) is becoming increasingly important for data scientists to explore graphs in real life, where a series of graph pattern matching (GPM) queries are created and submitted in an interactive manner based on the insights provided by the prior queries. To solve the iGPM problem, three key considerations must be taken into account: performance, usability and scalability, namely if results can be returned in a timely manner, if queries can be written in a declarative way without the need of imperative fine-tune, and if it can work on large graphs. In this paper, we propose the GLogS system that allows users to interactively submit queries using a declarative language. The system will compile and automatically compute optimal execution plans for the queries, and execute them on an existing distributed dataflow engine. In the evaluation, we compare GLogS with the alternatives systems Neo4j and TigerGraph.
featured: true
publication: "USENIX Annual Technical Conference (ATC) 2023 (to appear)"
tags: ["Graph", "pattern matching", "interactive system", "query optimization", "graph sparsification"]
---

