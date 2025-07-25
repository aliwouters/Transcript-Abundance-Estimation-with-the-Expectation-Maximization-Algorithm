# Transcript-Abundance-Estimation-with-the-Expectation-Maximization-Algorithm
This project applies the Expectation-Maximization (EM) algorithm to estimate the relative abundances of RNA isoforms based on RNA-seq read data. The task involved modeling how sequencing reads map to two transcript isoforms with different effective lengths, then iteratively computing transcript proportions using the RSEM (RNA-Seq by Expectation-Maximization) framework.

The project included both a manual derivation and a Python implementation of the EM algorithm. Multiple configurations were explored:

In one case, isoform lengths differed, leading to biased abundance estimates due to transcript length affecting read mapping probabilities.

In another case, equal-length isoforms resulted in even read assignment and unbiased estimates.

By simulating read compatibility and running the EM algorithm over 100 iterations, the project demonstrated how transcript length influences abundance inference in RNA-seq analysis, and how EM can iteratively refine these estimates based on observed data.
