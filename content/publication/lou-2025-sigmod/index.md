---
title: "Towards a Converged Relational-Graph Optimization Framework"
date: 2024-10-30
publishDate: 2024-10-30T01:41:34.981585Z
authors: ["Yunkai Lou", "Longbin Lai", "Bingqing Lyu", "Yufan Yang", "Xiaoli Zhou", "Wenyuan Yu","Ying Zhang", "Jingren Zhou"]
publication_types: ["1"]
abstract: The recent ISO SQL:2023 standard adopts SQL/PGQ (Property Graph Queries), facilitating graph-like querying within relational databases. This advancement, however, underscores a significant gap in how to effectively optimize SQL/PGQ queries within relational database systems. To address this gap, we extend the foundational SPJ (Select-Project-Join) queries to SPJM queries, which include an additional matching operator for representing graph pattern matching in SQL/PGQ. Although SPJM queries can be converted to SPJ queries and optimized using existing relational query optimizers, our analysis shows that such a graph-agnostic method fails to benefit from graph-specific optimization techniques found in the literature. To address this issue, we develop a converged relational-graph optimization framework called RelGo for optimizing SPJM queries, leveraging joint efforts from both relational and graph query optimizations. Using DuckDB as the underlying relational execution engine, our experiments show that RelGo can generate efficient execution plans for SPJM queries. On well-established benchmarks, these plans exhibit an average speedup of 21.90x compared to those produced by the graph-agnostic optimizer.
featured: true
url_pdf: files/relgo-sigmod25.pdf
publication: "ACM SIGMOD/PODS International Conference on Management of Data 2025 (to appear)"
doi: "10.1145/3698828"
tags: ["Relational database", "Graph database", "Graph pattern matching", "Query optimization"]
---
