# Relevance Queries for Interval Data

<p align="justify">
  A wide range of applications manage large collections of interval data. For instance, temporal databases manage validity intervals of objects or versions thereof, while in probabilistic databases attribute values of records are associated with confidence or uncertainty intervals. The main search operation on interval data is the retrieval of data intervals that intersect (i.e., overlap with) a query interval (e.g., find records which were valid in September 2020, find temperature readings with non-zero probability to be within [24, 26] degrees). As query results could be many, we need mechanisms that filter or order them based on how relevant they are to the query interval. We define alternative relevance scores between a data and a query interval based on their (relative) overlap. We define relevance queries, which compute only a subset of the most relevant intervals that intersect a query. Then, we propose a framework for evaluating relevance queries that can be applied on popular domain-partitioning interval indices (interval tree and HINT). We present experiments on real datasets that demonstrate the efficiency of our framework over baseline approaches.
</p>
<figure>
  <img src="./figures/framework.jpg" width="500" alt="framework" />
</figure>

Source code from the following publication:
- <p align="justify">Panagiotis Bouros and Nikos Mamoulis, <i>Relevance Queries for Interval Data</i>, Proceedings of the ACM on Management of Data (PACMMOD), https://doi.org/10.1145/3725343, Vol 3, No 3, June 2025.<br> 
  To be presented at the 2025 ACM International Conference on Management of Data (ACM SIGMOD'25), Berlin, Germany, June 22-27, 2025</p>

## Source code coming soon
