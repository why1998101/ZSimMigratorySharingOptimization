## ZSim with Migratory Sharing Optimization

###### by Zhuoyu Ji (zhuoyuj) and Haoyang Wang (haoyang4)

#### We modify the ZSim cache simulator to add a migratory sharing optimization feature. This feature implements an algorithm to detect migratory objects and improve performance of accessing migratory objects by reducing the number of invalidations in the cache system.

### Deliverables

#### Modified ZSim source code with the migratory sharing optimization feature.
#### Micro-benmark programs and ZSim outputs of running those micro-benchmarks.
#### A report with analysis on the optimization and experimental evaluation results.

### References

##### Per Stenström, Mats Brorsson, and Lars Sandberg. 1993. An adaptive cache coherence protocol optimized for migratory sharing. SIGARCH Comput. Archit. News 21, 2 (May 1993), 109–118. https://doi.org/10.1145/173682.165147

##### [ZSim source](https://github.com/s5z/zsim) and [tutorials](http://zsim.csail.mit.edu/tutorial/)
##### [Ziqi Wang's Article](https://wangziqi2013.github.io/article/2019/12/25/understand-zsim-cc-sim.html)

### Legacy Documents

##### This project was originally targeting on other optimizations on ZSim as showned in those legacy documents.

##### [Proposal](https://github.com/why1998101/ParallelCacheSimulator/blob/main/Project_Proposal.pdf)
##### [Milestone](https://github.com/why1998101/ParallelCacheSimulator/blob/main/Milestone_Report.pdf)
