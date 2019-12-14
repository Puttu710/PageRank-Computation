# PageRank-Computation

This project involves finding page rank by implementing OpenMp .Our approach is an implementation of the research paper whose details are mentioned in the project report.

The algorithm used follows two kind of comparisons:

a) Baseline Algo(Iterative) vs Parallel Baseline Algo: The baseline algorithm is an iterative approach to find the pagerank ,while the parallel Baseline Algo is just the openmp implementation of the baseline algorithm.

    
b) Optimized Algo(Iterative) vs Parallel Optimized Algo: In optimized algorithm we first find strongly connected components in the graph and then use topological sort to divide graph into different levels as described in report.Now in parallel version we can run all strongly connected components within each level at same time.

   
